# Security Detective Challenge

## Question 1
Answer: I am [your username]. My home folder is [your home folder].
Commands: whoami, pwd

## Question 2
Answer: The server name is [hostname]. The Ubuntu version is [version].
Commands: hostname, cat /etc/os-release

## Question 3
Answer: The RAM information is [your RAM result]. The free disk space is [your disk result].
Commands: free -h, df -h /

## Question 4
Answer: The users with /bin/bash are [list the usernames].
Command: grep '/bin/bash' /etc/passwd

## Question 5
Answer: The command returned [number] lines, including the header.
Command: ps aux | wc -l

## Question 6
Answer: The creation time is [time from logs]. The deletion time is [time from logs, if available].
Command: sudo grep lab5user /var/log/auth.log
