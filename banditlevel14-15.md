#Bandit level 14-15 write-up

##Objective: Find the password for next level from localhost in the server at port 30000
##Steps taken: 1.Connecting to server

Used the SSH command to login to the server with the provided password

Command: ssh bandit14@bandit.labs.overthewire.org -p 2220

2.Connecting to localhost at port 30000

Using nc command connected to the localhost at port 30000 and entered the password and found the password for next level

Command:nc localhost 30000
