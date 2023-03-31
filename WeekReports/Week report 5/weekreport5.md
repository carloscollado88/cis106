---
Name: Carlos Collado
Course: CIS 106
Semester: Spring 2023
Instructor: Roberto Alberto
---

# Week Report 5

## Answer to questions:

* **What are Command Options?**

Command options are commands used to pass parameters to a program. These entries, also called command-line switches, can pass along cues for changing various settings or executing commands in an interface.

* **What are Command Arguments?**

Command arguments are extra commands you can use when launching a  program so that the program's functionality will change. These arguments can be used to add more features that includes specifying a file that output should be logged to, specifying a default document to launch, or to enable features that may be a bit buggy for normal use.

* **Which command is used for creating directories? Provide at least 3 examples.**

The command to create directories is `mkdir`
  
* Example #1
   * `mkdir ~/work`

* Example #2
*To create multiple directories*
    * `mdkir -p ~/work/templates ~/work/important/classified` 

* Example #3
*To create directories with space in name*
    * `mkdir ~/work/new\ documents`

* **What does the touch command do? Provide at least 3 examples.**

The `touch` command create files with any extension desire by the user such as pdf, png, jpg, txt, docs, etc.

* Example #1
    * `touch image.png`

* Example #2
*Create file inside a directory*
    * `touch ~/work/welcome.txt`

* Example #3
*To create a file with space in the name*  
    * `touch "list of pending tasks.txt"`


* **How do you remove a file? Provide an example.**

Files are remove by using the `rm` command. For example: `rm ~/work/templates`

* **How do you remove a directory and can you remove non-empty directories in Linux? Provide an example**

To remove a directory you can use `rmdir` if the directory is empty or `rm` with the `-r` option if the directory contains files.

Example: `rm -r ~/work` or `rmdir ~/work`

* **Explain the mv and cp command. Provide at least 2 examples of each**


The `mv` command works to move files and directories, but can also be use to change name. 

*To move a file to a different directory*
Example 1: `mv /Downloads/picture1.png /Pictures/picture1.png`

*To move and change the file name at the same time*
Example 2: `mv /Downloads/picture1.png /Picture/image1.png`

The `cp` command is use to copy the files to another directory.

*To copy the file to another directory*
Example 1: `cp Downloads/picture1.png Pictures/`

*To copy the file with absolute path*
Example 2: `cp ~/Downloads/picture1.png ~/Pictures/`

# **Practice 1**

![practice1](practice%201.1.png)

# **Practice 2**

![practice2](practice%202.1.png)

# **Practice 3**

![practice3.1](practice%203.1.png)
![practice3.2](practice%203.2.png)

# **Practice 4**

![practice4.1](practice%204.1.png)
![practice4.2](practice%204.2.png)