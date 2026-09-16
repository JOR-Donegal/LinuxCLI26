# File Permissions

__cp__ _file1 file2_ is the command which makes a copy of _file1_ in the current working directory and calls it _file2_.

We are going to create a file called __File1.txt__ in your home directory, and use the __cp__ command to copy it to your __Exercise1__ directory.

First, change to your home directory using the command

````linux
cd ~
````

then use the __cat__ command to create the __file1.txt__ file with some contents. Type the lines exactly as I have, including mistakes, case and punctuation. To start, type;

````linux
cat > file1.txt
````

When you are finished, press

__[ctrl][d]__

to save and exit.

<figure>
<img src = "https://jor-donegal.github.io/LinuxCLI26/images/fig3.jpg">
<figcaption>Fig 3. Sample content.</figcaption>
</figure>

The quote is from “As you like it”, Shakespeare!

Now, change your working directory to your Exercise1 directory

````linux
cd ~/Exercise1
````

Then copy the file you just created (~/file1.txt) to the __Exercise1__ directory by typing the command

````linux
/cp ~/file1.txt .
````

Be careful, the format of the command is __cp__ _[source] [destination]_

<figure>
<img src = "https://jor-donegal.github.io/LinuxCLI26/images/fig4.jpg">
<figcaption>Fig 4. Output.</figcaption>
</figure>

Look at the example above, it copies the source “~/File1.txt” to the destination “.”

Don't forget the dot at the end! Remember, in Linux, the dot means the current directory.
The above command means copy the file __File1.txt__ to the current directory, keeping the name the same. Do a __ls__ or __ll__ to check that this worked.

## Exercise

In your _~/Exercise1_ directory, create a backup of your __file1.txt__ file by copying it to a file called __file1.bak__

Then delete the __file1.txt__ file in your home directory (not the one in the Exercise1 directory).
