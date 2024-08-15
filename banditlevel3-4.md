#Bandit level 3-4 write-up

##Objective: Find the password for next level from a hidden file in inhere directory

##Steps taken: 1.Connecting to server

Used the SSH command to login to the server with the provided password

Command: ssh bandit3@bandit.labs.overthewire.org -p 2220

2.Finding the directory named "inhere"

Using ls command found the directory named "inhere" in the directory

Command:ls

3.Opening the directory named "inhere"

Using cd command opened the directory named "inhere" 

Command:cd inhere

4.Finding the hidden file inside the directory

Using ls -a command found the hidden file named "...Hiding-From-You" in the directory 

Command: ls -a

5.Opening the hidden file

Using cat command opened the file named "...Hiding-From-You" and found the password for next level

command: cat ...Hiding-From-You

