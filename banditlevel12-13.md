#Bandit level 12-13 write-up

##Objective: Find the password for next level from a file called "data.txt" which is a hexdump of a file that has been repeatedly compressed. 

##Steps taken: 1.Connecting to server

Used the SSH command to login to the server with the provided password

Command: ssh bandit12@bandit.labs.overthewire.org -p 2220

2.Finding the file

Using ls command found the file data.txt

Command:ls

3.Creating temp directory

Using mktemp command created temp directory

Command:mktemp -d
