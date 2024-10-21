# Terminal Commands

For more info in each of the commands you can use the manual ```man```  for each of the commands below.
Example: ```man traceroute```


| Description                                                                            | Command                                 |
|----------------------------------------------------------------------------------------|-----------------------------------------|
| __Network__                                                                            |                                         |
| To see if a site is up and running                                                     | `ping <domain>`                         |
| To trace the path to a domain, or see delays                                           | `traceroute <domain>`                   |
| To get more info from a domain                                                         | `netstat <domain>`                      |
| To get the nameservers for a domain                                                    | `nslookup <domain>`                     |
| To get the dns records for a domain                                                    | `dig <domain>`                          |
| __Processes__                                                                          |                                         |
| To find a process running in the process list.  The result will provide you with an id | `ps -aux \| grep <process_name> `       |
| To stop/kill a process                                                                 | `kill -9 <process_id>`                  |
