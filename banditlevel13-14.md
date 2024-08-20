#Bandit level 12-13 write-up

##Objective: Find the password for next level from a file called bandit14 which is only accessible by user named bandit14

##Steps taken: 1.Connecting to server

Used the SSH command to login to the server with the provided password

Command: ssh bandit13@bandit.labs.overthewire.org -p 2220

2.Finding the file

Using ls command found the sshkey.private

Command:ls

3.Opened the file

Using cat opened the file and found the private key and copied it

Command:cat sshkey.private 

4.Created key file

Exited the server and created a file using nano command and saved the key and gave permissions using chmod command

Command:nano bandit14<br>
        chmod 600 bandit14

5.Connecting the server

Connected to the server using ssh server 

Command: ssh -i bandit14 bandit14@bandit.labs.overthewire.org -p 2220

6.Opening the file with password in it

Using cat command open the file and got the password for next level

Command:cat /etc/bandit_pass/bandit14

