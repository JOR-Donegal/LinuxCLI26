# Moving Files

__mv__ _[file1] [file2]_ moves (or renames) _file1_ to _file2_

To move a file from one place to another, use the mv command. This has the effect of moving rather than copying the file, so you end up with only one file rather than two. It can also be used to rename a file, by moving the file to the same directory, but giving it a different name. We are now going to move the file file1.bak to your backup directory.
First, change working directory to your _Exercise1_ directory (can you remember how?). Check the contents!

<figure>
<img src = "https://jor-donegal.github.io/LinuxCLI26/images/fig5.jpg">
<figcaption>Fig 5. Output.</figcaption>
</figure>

Then, inside the Exercise1 directory, type

````linux
mv file1.bak backups/
````

<figure>
<img src = "https://jor-donegal.github.io/LinuxCLI26/images/fig6.jpg">
<figcaption>Fig 6. Output.</figcaption>
</figure>
