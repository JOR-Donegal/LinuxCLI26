# Paths

You will recall that

- (.) means the current directory, so typing __cd .__ means stay where you are.
- (..) means the parent of the current directory, so typing __cd ..__ will take you one directory up the hierarchy.

We have used the term _working directory_ previously to describe the current working directory the _shell_ is operating in.
In Linux we can use the command __pwd__ to show our working directory.

Before we type a command, we really need to know what our current directory is. We have several types of paths and I will briefly explain them now. An _absolute path_ is the path to a file with respect to the root. If I want to delete a file deep in my directory structure, I can type

__del /home/john.oraw/CLI/rubbish.txt__

and regardless of which working directory I am in, this will work.

I can also delete a file using a path relative to my working directory. Suppose I have a working directory of __/home/john.oraw/CLI__

and I want to delete the same file as above. I could type

__del ./CLI/rubbish.txt__

and this would still work.
