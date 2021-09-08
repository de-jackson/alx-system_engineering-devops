# General Requirements
* Allowed editors: vi, vim, emacs
* All your scripts will be tested on Ubuntu 20.04 LTS
* All your scripts should be exactly two lines long ($ wc -l file should print 2)
* All your files should end with a new line (why?)
* The first line of all your files should be exactly #!/bin/bash
* A README.md file, at the root of the folder of the project, describing what each script is doing
* You are not allowed to use backticks, &&, || or ;
* All your files must be executable

# Tasks

# 0. My name is Betty
Create a script that switches the current user to the user betty.

* You should use exactly 8 characters for your command (+1 character for the new line)
* You can assume that the user betty will exist when we will run your script<br>
julien@ubuntu:/tmp/h$ tail -1 0-iam_betty | wc -c<br>
9<br>
julien@ubuntu:/tmp/h$<br>

# 1. Who am I
Write a script that prints the effective username of the current user.<br>

julien@ubuntu:/tmp/h$ ./1-who_am_i<br>
julien<br>
julien@ubuntu:/tmp/h$<br> 

# 2. Groups
Write a script that prints all the groups the current user is part of.<br>

julien@ubuntu:/tmp/h$ ./2-groups<br>
julien adm cdrom sudo dip plugdev lpadmin sambashare<br>
julien@ubuntu:/tmp/h$<br>
Note: depending on the user, you will get a different output.<br>

# 3. New owner
Write a script that changes the owner of the file hello to the user betty.

# 4. Empty!
Write a script that creates an empty file called hello.

# 5. Execute
Write a script that adds execute permission to the owner of the file hello.

* The file hello will be in the working directory<br>
julien@ubuntu:/tmp/h$ ls -l<br>
total 8<br>
-rwxrw-r-- 1 julien julien 28 Sep 20 14:26 5-execute<br>
-rw-rw-r-- 1 julien julien 23 Sep 20 14:25 hello<br>
julien@ubuntu:/tmp/h$ ./hello<br>
bash: ./hello: Permission denied<br>
julien@ubuntu:/tmp/h$ ./5-execute<br>
julien@ubuntu:/tmp/h$ ls -l<br>
total 8<br>
-rwxrw-r-- 1 julien julien 28 Sep 20 14:26 5-execute<br>
-rwxrw-r-- 1 julien julien 23 Sep 20 14:25 hello<br>
julien@ubuntu:/tmp/h$ <br>

# 6. Multiple permissions
Write a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.

* The file hello will be in the working directory

# 7. Everybody!
Write a script that adds execution permission to the owner, the group owner and the other users, to the file hello

* The file hello will be in the working directory
* You are not allowed to use commas for this script

# 8. James Bond
Write a script that sets the permission to the file hello as follows:

* Owner: no permission at all
* Group: no permission at all
* Other users: all the permissions
* The file hello will be in the working directory You are not allowed to use commas for this script

# 9. John Doe
Write a script that sets the mode of the file hello to this:<br>
-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello<br>
* The file hello will be in the working directory
* You are not allowed to use commas for this script

# 10. Look in the mirror
Write a script that sets the mode of the file hello the same as olleh’s mode.

* The file hello will be in the working directory
* The file olleh will be in the working directory

# 11. Directories
Create a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.

# 12. More directories
Create a script that creates a directory called my_dir with permissions 751 in the working directory.

# 13. Change group
Write a script that changes the group owner to school for the file hello

* The file hello will be in the working directory

# 






