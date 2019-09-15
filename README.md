# password-less-ssh-automated
Automate password less SSH between thousands of servers

# Script to automate password-less SSH among many servers.
 The script:
   - Logs into servers from the server_list list.
   - Generates SSH keys
   - Uploads the public key to all other servers from the server_list list

# Usage:
   Edit server_list to specific IP address or hostname of servers. Save and
   run the script using expect <filename>. The script will ask password to
   login to the servers. Local user is used by default.

# Assumption:
   Same user and password on all servers. Script can be enhanced
   for different user/password on different servers

# Requirements:
   Expect
