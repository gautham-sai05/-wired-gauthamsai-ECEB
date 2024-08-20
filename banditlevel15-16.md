#Bandit level 15-16 write-up

##Objective: Find the password for next level from localhost in the server at port 30001 encrypted by SSL/TLS
##Steps taken: 1.Connecting to server

Used the SSH command to login to the server with the provided password

Command: ssh bandit15@bandit.labs.overthewire.org -p 2220

2.Connecting to localhost at port 30001 

Using openssl command connected to the localhost at port 30001 and entered the password and found the password for next level

Command:openssl s_client -connect localhost:30001
