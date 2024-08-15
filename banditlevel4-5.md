#Bandit level 4-5 write-up

##Objective: Find the password for next level from only human-readable file in inhere directory

##Steps taken: 1.Connecting to server

Used the SSH command to login to the server with the provided password

Command: ssh bandit4@bandit.labs.overthewire.org -p 2220

2.Finding the directory named "inhere"

Using ls command found the directory named "inhere" in the directory

Command:ls

3.Opening the directory named "inhere"

Using cd command opened the directory named "inhere"

Command:cd inhere

4.Finding the human-readable file inside the directory

Using file command found the files inside inhere which contained ASCII text

Command: file ./*

5.Opening the human-readable file

Using cat command opened the file named "-file07" and found the password for next level

command: cat ./-file07
