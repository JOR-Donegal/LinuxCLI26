# Hidden Files

ls does not, in fact, cause all the files in your home directory to be listed, but only those ones whose name does not begin with a dot (.)

Files beginning with a dot (.) are known as _hidden files_ and usually contain important program configuration information.
They are hidden because you should not change them unless you are very familiar with Linux!!!

To list all files in your home directory including those whose names begin with a dot, type

````linux
ls -a
````

<figure>
<img src = "https://jor-donegal.github.io/LinuxCLI26/images/fig2.jpg">
<figcaption>Fig 2. ls -a output.</figcaption>
</figure>

As you can see, __ls -a__ lists files that are normally hidden.

ls is an example of a command which can take options: __-a__ is an example of an option. The options change the behavior of the command. There are online manual pages that tell you which options a command can take, and how each option modifies the behavior of the command. (See later in this tutorial).
