# 0x00. Shell, basics
Requirements
General
Allowed editors: vi, vim, emacs
All your scripts will be tested on Ubuntu 20.04 LTS
All your scripts should be exactly two lines long ($ wc -l file should print 2)
All your files should end with a new line (why?)
The first line of all your files should be exactly #!/bin/bash
A README.md file at the root of the repo, containing a description of the repository
A README.md file, at the root of the folder of this project, describing what each script is doing
You are not allowed to use backticks, &&, || or ;
All your scripts must be executable. To make your file executable, use the chmod command: chmod u+x file. Later, we’ll learn more about how to utilize this command

# Task 0
Write a script that prints the absolute path name of the current working directory.

# Task 1
Display the contents list of your current directory.

Example:

$ ./1-listit
Applications    Documents   Dropbox Movies Pictures
Desktop Downloads   Library Music Public
$

#Task 2
Write a script that changes the working directory to the user’s home directory.

You are not allowed to use any shell variables

# Task 3
Display current directory contents in a long format

Example:

$ ./3-listfiles
total 32
-rwxr-xr-x@ 1 sylvain staff 18 Jan 25 00:19 0-current_working_directory
-rwxr-xr-x@ 1 sylvain staff 19 Jan 25 00:23 1-listit
-rwxr-xr-x@ 1 sylvain staff 18 Jan 25 00:29 2-bring_me_home
-rwxr-xr-x@ 1 sylvain staff 18 Jan 25 00:39 3-listfiles
$

# Task 4
Display current directory contents, including hidden files (starting with .). Use the long format.

Example:

$ ./4-listmorefiles
total 32
drwxr-xr-x@ 6 sylvain staff 204 Jan 25 00:29 .
drwxr-xr-x@ 43 sylvain staff 1462 Jan 25 00:19 ..
-rwxr-xr-x@ 1 sylvain staff 18 Jan 25 00:19 0-current_working_directory
-rwxr-xr-x@ 1 sylvain staff 19 Jan 25 00:23 1-listit
-rwxr-xr-x@ 1 sylvain staff 18 Jan 25 00:29 2-bring_me_home
-rwxr-xr-x@ 1 sylvain staff 18 Jan 25 00:39 3-listfiles
-rwxr-xr-x@ 1 sylvain staff 18 Jan 25 00:41 4-listmorefiles
$

# Task 5
Display current directory contents.

Long format
with user and group IDs displayed numerically
And hidden files (starting with .)

# Task 6
Create a script that creates a directory named my_first_directory in the /tmp/ directory.

# Task 7
Move the file betty from /tmp/ to /tmp/my_first_directory.

# Task 8
Delete the file betty.

The file betty is in /tmp/my_first_directory
Example:

$ ./8-firstdelete
$ ls /tmp/my_first_directory/
$

# Task 9
Delete the directory my_first_directory that is in the /tmp directory.

# Task 10
Write a script that changes the working directory to the previous one.

# Task 11
Write a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.

# Task 12
Write a script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script.

# Task 13
Create a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory.

# Task 14
Create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.

You can consider that all HTML files have the extension .html

# Task 15

