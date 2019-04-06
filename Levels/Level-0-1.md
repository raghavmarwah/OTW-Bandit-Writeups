# Bandit Level 0 to 1

![Beep Level-0-1-Instructions](Images/Levels-0-1-ins/png "LEVEL 0 to 1 Instructions")
This is quite an easy level as expected, all we need to do here is to connect
to the Bandit servers via SSH on port 2220 and then retieve the readme file in
the home directory to get the password for Level 1

`ssh bandit.labs.overthewire -p 2220 -l bandit0`

The ssh will promt for the password, just enter `bandit0`

`ls -al` Running this command shows us all  the files in the home directory
with the permission details as well, we can see the readme file there.

`cat readme` display the contents of the file in terminal.

And there we we get the password for the next level.
