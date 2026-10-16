# Security Detective Challenge



## Question 1

Answer: [Write the username and home folder from your actual output.]

Commands: `whoami`, `pwd`



## Question 2

Answer: [Write your server hostname and Ubuntu version.]

Commands: `hostname`, `cat /etc/os-release | head -2`



## Question 3

Answer: [Write total RAM and available disk space.]

Commands: `free -h`, `df -h /`



## Question 4

Answer: [List the usernames whose login shell is /bin/bash.]

Command: `grep '/bin/bash' /etc/passwd`



## Question 5

Answer: [Write the process count from your command output.]

Command: `ps aux | wc -l`



## Question 6

Answer: [Write the recorded creation and deletion times for lab5user, if available in the security log.]

Commands: `sudo grep lab5user /var/log/auth.log`, `sudo grep lab5user /var/log/auth.log | tail -5`


