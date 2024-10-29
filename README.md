# Terminal Commands

For more info in each of the commands you can use the manual ```man```  for each of the commands below.
Example: ```man traceroute```


| Description                                                                                                     | Command                                                            |
|-----------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------|
| __Network__                                                                                                     |                                                                    |
| To get the status of a network host                                                                             | `ping <domain>`                                                    |
| To trace the path to a domain                                                                                   | `traceroute <domain>`                                              |
| To get network status                                                                                           | `netstat <domain>`                                                 |
| To get the nameservers for a domain                                                                             | `nslookup <domain>`                                                |
| To get the dns records for a domain                                                                             | `dig <domain>`                                                     |
| __Processes__                                                                                                   |                                                                    |
| To find a process running in the process list.  The result will provide you with an id                          | `ps -aux \| grep <process_name> `                                  |
| To stop/kill a process                                                                                          | `kill -9 <process_id>`                                             |
| __Security__                                                                                                    |                                                                    |
| Creating a SSH Key                                                                                              | `ssh-keygen -t <algorith_type> -b <key_size>`                      |
| Two switch to root                                                                                              | `sudo -i`                                                          |
| __Reading File__                                                                                                |                                                                    |
| Outputs last part of the file                                                                                   | `tail`                                                             |
| Outputs the first part of the file                                                                              | `head`                                                             |
| Outputs the data in pages                                                                                       | `less`                                                             |
| Outputs the complete data in a file                                                                             | `cat`                                                              |
