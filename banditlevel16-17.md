#Bandit level 16-17 write-up

##Objective: Find the password for next level from localhost in the server at a por between 31000 to 32000
##Steps taken: 1.Connecting to server

Used the SSH command to login to the server with the provided password

Command: ssh bandit16@bandit.labs.overthewire.org -p 2220

2.Finding the apporpriate port

Using nmap command found the ports that are open

Command:nmap -p 31000-32000 localhost and found the working port by trail and error

 3.Connecting to the port

Using ncat command connected to the localhost at port 31790 and entered the password and found the security key  for next level

Command:ncat --ssl localhost 31790
