#Bandit level 5-6 write-up

##Objective: Find the password for next level from a file with given specification in inhere directory

##Steps taken: 1.Connecting to server

Used the SSH command to login to the server with the provided password

Command: ssh bandit5@bandit.labs.overthewire.org -p 2220

2.Finding the directory named "inhere"

Using ls command found the directory named "inhere" in the directory

Command:ls

3.Opening the directory named "inhere"

Using cd command opened the directory named "inhere"

Command:cd inhere

4.Finding the specific file inside the directory

Using file command found the file inside maybehere07 directory in inhere

Command: find -type f -size 1033c -readable ! -executable

5.Opening the file named .file2

Using cat command opened the file named ".file2" and found the password for next level

command: cat .file2
