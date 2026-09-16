# Directories

To keep our files organized, we need to be able to make and delete directories. We also need to be able to change working directory as required. Note that commands in Unix and DOS are similar but not the same. In either operating system, the tree command gives a nice overview of the directory tree structure from the working directory down. 
The command __cd__ _directoryname_ changes the working directory. 
The command __mkdir__ _subdirectory_ makes a new directory.
The command __rmdir__ _subdirectory_ removes a sub directory.

## Exercise

Go to you home directory.

1. Create a directory called __CLI__
2. Change your working directory to __CLI__
3. Create a directory called __Backup__ under the directory CLI
4. Create a directory called __Test__ under the directory CLI
5. Return to your home directory by typing __cd__. You will often see __cd ~__ used, it has the same effect.
6. Use the __tree__ command to review what you have done.
7. Delete the directory called __Test__, you may have to navigate to it!
8. Check the result of the command __cd ..__
9. In either operating system, __cd /__ should bring you back to the root.
