#Bandit level 6-7 write-up

##Objective: Find the password for next level from a file that is present somewhere in the server

##Steps taken: 1.Connecting to server

Used the SSH command to login to the server with the provided password

Command: ssh bandit6@bandit.labs.overthewire.org -p 2220

2.Finding the specific file 

Using find command found the specified file

Command:find / -size 33c -group bandit6 -user bandit7

3.Opening the file

 Using cat command opened the file and found the password for next server 

 Command:cat ./var/lib/dpkg/info/bandit7.password
