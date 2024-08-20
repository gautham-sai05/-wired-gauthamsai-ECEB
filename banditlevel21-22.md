#Bandit level 21-22 write-up

##Objective: A program is running automatically at regular intervals from cron, the time-based job scheduler. Look in /etc/cron.d/ for the configuration and see what command is being executed

Used the SSH command to login to the server with the provided password

Command: ssh bandit21@bandit.labs.overthewire.org -p 2220

2.Opened the directory

Using cd command Opened the directory

Command:cd /etc/cron.d/

3.Finding the file

Found the file using ls command

Command:ls -l

3.Opening the file

Using cat command opened the file and found the directory command it was repeating

Command:cat cronjob_bandit22

4.Opening the command file

Using cat command opened the file which contained the code that was repeating,opened the directory found inside it and found the password for the next level

Command:cat /usr/bin/cronjob_bandit22.sh<br>
        cat /tmp/t7O6lds9S0RqQh9aMcz6ShpAoZKF7fgv
