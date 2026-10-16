
# Security Detective Challenge

## Question 1
Answer: I am logged in as muskanzeeshan. My home folder is /home/muskanzeeshan.
Commands: whoami, pwd

## Question 2
Answer: My server name and Ubuntu version are shown by the commands below.
Commands: hostname, cat /etc/os-release | head -2

## Question 3
Answer: The RAM amount and available disk space are shown by the commands below.
Commands: free -h, df -h /

## Question 4
Answer: The users whose login shell is /bin/bash are listed below.
Command: grep '/bin/bash' /etc/passwd

## Question 5
Answer: The number of running processes is shown by the command below.
Command: ps aux | wc -l

## Question 6
Answer: The security log records the creation and sudo attempt for lab5user. The deletion time may not be recorded in this log.
Command: sudo grep lab5user /var/log/auth.log

