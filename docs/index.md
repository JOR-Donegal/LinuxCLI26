# Introduction

!!! abstract "Linux CLI"

We need to be able to work at the command prompt for some tasks, in Windows, Unix of any form, or on appliances and communications equipment.

In DOS, we had a command processor. It may be a little more complex under Windows, but in pure DOS we have a programme called COMMAND.COM which interprets many of the basic commands. In Windows, we open a special command window to access the prompt. When a user logs in, the login program checks the username and password, and then starts another program called the _shell_. The shell is a _command line interpreter_ (CLI). It interprets the commands the user types in and arranges for them to be carried out. The shell acts as an interface between the user and the kernel.

In our UNIX examples, we use the _bash shell_, however there are many others in common use including the _Bourne Shell_ and the _C Shell_. Each command at the command prompt refers to a programme or routine within the operating system, these are _internal commands_. With some commands it is possible to include parameters after the command, these are referred to as _arguments_. For more complex commands, they are _external_ to the OS.

When you type a command, you run that programme and when it terminates, the shell gives the user another prompt. A user can customize their own shell, and users can use different shells on the same machine. The shell keeps a list of the commands you have typed in. If you need to repeat a command, use the cursor keys to scroll up and down the list or type __history__ for a list of previous commands.

If you need detailed help at any time, every Linux system has manual pages. When you are doing exercises later on a live system, type the man command and do a little research on it.