# Input and Output Redirection

In almost all command line environments, we have the concept of

1. A standard input device, normally the keyboard (STDIN=0)
2. A standard output device, normally the screen (STDOUT=1)
3. A standard error device, also normally the screen (STDERR=2)

You may have seen these in the Linux shell, and we can also use them in Windows/DOS. At the command prompt, try typing  

````linux
ls -l > rubbish.txt
````

and check what happened by typing __ls__. You should have a new file called _rubbish.txt_ with whatever the output of the __ls -l__ command was. You can check the contents with the command
__more rubbish.txt__

and you should do this. We have redirected the output of a command to a file using the operator __>__. This operator will create or overwrite the file. If we use the __>>__ operator, it will append to the file.

Now try the __help__ command and look through the output. We need to become familiar with some of these commands, but we need to know how to identify all of them. Type

__help > MyHelpFile.txt__

and check to see that you have created a text file with a full listing of commands.
