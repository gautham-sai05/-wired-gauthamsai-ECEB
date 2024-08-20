#Bandit level 19-20 write-up

##Objective: The password for this level can be found in the usual place (/etc/bandit_pass), after you have used the setuid binary.

##Steps taken: 1.Connecting to server

Used the SSH command to login to the server with the provided password

Command: ssh bandit19@bandit.labs.overthewire.org -p 2220

2.Finding the files

Using ls command found the file that is Setuid Binary

Command:ls -l

3.Opening the file

Executing the binary file

Command:./bandit20-do 

4.Opening the file containing password using the binary file and found the password for next level

Command:./bandit20-do cat /etc/bandit_pass/bandit20

