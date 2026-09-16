# Wildcards

When searching for files (or copying or removing) it can be very handy to use wildcards.

The (*) symbol (pronounced splat) is probably the most common.

For example

````linux
ls *.txt
````

would return all text files? Because of extensions, wildcards behave a bit differently between DOS and Unix.

The command

````linux
ls *.txt
````

shows all files ending in .txt and is case sensitive. A file called _fish.cakes_ could be a text file, we have no way to know from its extension.

The command

````linux
ls R*.txt
````

shows all files beginning with capital _R_ and with an extension _.txt_

If you use the symbol __*__ on its own, it means all files in the working directory.

The character __?__ will match exactly one character. So “?ouse” will match files like house and mouse, but not grouse. Try typing

````linux
ls ?list
````

## Exercise

Delete all files in the _CLI/Backup_ directory, then copy all files from CLI directory to _CLI/Backup_ directory.