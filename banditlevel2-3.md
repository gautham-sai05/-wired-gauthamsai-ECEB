#Bandit level 2-3 write-up

##Objective: Find the password for next level from file named "spaces in this filename"

##Steps taken: 1.Connecting to sever

Used the SSH command to login to the server with the provided password

Command: ssh bandit2@bandit.labs.overthewire.org -p 2220

2.Finding the file named "spaces in this filename"

Using ls command found the file named "spaces in this filename" in the directory

Command:ls

3.Opening the file named "spaces in this filename"

Using cat command opened the file named "spaces in this filename" in the directory and found the password for the server in next level

Command:cat "spaces in this filename"
