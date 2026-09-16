# Moving around directories

We will now examine how to move files around using these commands. Before starting, make sure you are in the __\CLI__ directory!

Examine these commands

- __cp rubbish.txt rubbish1.txt__
- __cp rubbish.txt Backup__

What was the difference in how the command was interpreted?

We can delete files in a directory which is not our working directory, using relative paths.

- __rm Backup/rubbish1.txt __
- __cp ../rubbish.txt .__
- __ll__

What happened and why?

In many cases, (.) and (..) are very handy, however they do require you to know what your working directory is. One longer but safer option is to use absolute path names. Try using absolute pathnames to copy the file _rubbish.txt_ to a backup directory