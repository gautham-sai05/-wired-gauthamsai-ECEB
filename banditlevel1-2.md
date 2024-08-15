#Bandit level 1-2 write-up

##Objective:
Find the password for next level from file named "-"

##Steps taken:
1.Connecting to sever

Used the SSH command to login to the server with the provided password

Command: ssh bandit1@bandit.labs.overthewire.org -p 2220

2.Finding the file named "-"

Using ls command found the file named "-" in the directory

Command:ls

3.Opening the file named "-"

Using cat command opened the file named "-" in the directory and found the password for the server in next level

Command:cat ./-
