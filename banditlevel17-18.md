#Bandit level 17-18 write-up

##Objective: There are 2 files in the homedirectory: passwords.old and passwords.new. The password for the next level is in passwords.new and is the only line that has been changed between passwords.old and passwords.new

##Steps taken: 1.Connecting to server

Used the SSH command to login to the server with the provided password

Command: ssh -i bandit16 bandit17@bandit.labs.overthewire.org -p 2220

2.Finding the files

Using ls command found the files

Command:ls

3.Compared the files

Using diff compared the file and found the password for next level

Command:diff passwords.old passwords.new


