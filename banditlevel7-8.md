#Bandit level 7-8 write-up

##Objective: Find the password for next level from a file called "data.txt" nearby the word millionth in it 

##Steps taken: 1.Connecting to server

Used the SSH command to login to the server with the provided password

Command: ssh bandit7@bandit.labs.overthewire.org -p 2220

2.Finding the file

Using ls command found the file data.txt

Command:ls

3.Finding password

Using grep command found the password

Command:grep "millionth" data.txt
