#Bandit level 20-21 write-up

##Objective: A binary file reads a line of text from the connection and compares it to the password in the previous level (bandit20). If the password is correct, it will transmit the password for the next level (bandit21)
##Steps taken: 1.Connecting to server

Used the SSH command to login to the server with the provided password

Command: ssh bandit20@bandit.labs.overthewire.org -p 2220

2.Creating a new pane and splitting the terminal

Using tmux command created a split screen for terminal

Command:tmux split-window -h 

3.Creating a listener on new pane

Using nc command created a listener in port 11223

Command:nc -lvp 11223

3.Connecting the to the port

Using the setuid binary to connect to the port on the old pane

Command:./suconnect 11223 

4.Entering the password 

Entered the password of current level on the new pane and gt the password for next level
