#Bandit level 11-12 write-up

##Objective: Find the password for next level from a file called "data.txt" where all lowercase (a-z) and uppercase (A-Z) letters have been rotated by 13 positions

##Steps taken: 1.Connecting to server

Used the SSH command to login to the server with the provided password

Command: ssh bandit11@bandit.labs.overthewire.org -p 2220

2.Finding the file

Using ls command found the file data.txt

Command:ls

3.Finding password

Using cat,tr commands and found the password

Command:cat data.txt | tr 'A-Za-z' 'N-ZA-Mn-za-m' 

