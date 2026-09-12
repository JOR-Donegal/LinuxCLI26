# The CLI

I assume you are using a server version of Linux/Unix and that you know how to get to the command prompt. If you are using a GUI version of Ubuntu, press [ctrl][t] to open a terminal.

In Unix if you type a command which is not understood, you get a response command not found, although other error messages are possible. Sometimes this will happen after you type a perfectly good command name. If the operating system does not know where to find the command, it will give you this error. More about this when we look at paths and environment variables a little bit later.

You need to be aware of the computer's response as we are going along. If the computer responds to a command with an error, go back and check the command again, it probably hasn't been carried out.

To find out what version of operating system you are running, in the Unix shell type __uname__ and press return

Note that

- All commands and file names in Unix are case sensitive.
- All commands and file names in DOS are NOT case sensitive.

## Working Environment

Be careful, but you can carry these exercises out on almost any computer, safely. You may be deleting files and directories, hence the warning! Do not practice on a production system!

If you are familiar with VMWare Workstation or Hyper-V, you can stand up some VMs to carry out this work, this is always the preferred approach.

Throughout these notes, adapt my instructions to wherever your home directory actually is.

Although WSL2 in Windows should be an option, it does load Virtualization components and you may have problems using VMWare Workstation afterwards. At the moment, we only recommend you use a single hypervisor.

## History

When you begin using the CLI, you will use shorcuts like [TAB] to finsih commands.

You can use the up and down arrows to scroll through previous commands; this is a great way of making your time at the command prompt more accurate and more efficient.

I use the command __history__ all the time. It shows me all the previous commands I have used. When I want to document work I have done on a system, I type

````linux
history > log.14JUN25
````

This give me a text file of all the commands I have carried out on 14/6/25 and allows me to document my work.
