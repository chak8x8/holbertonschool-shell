Holberton Shell Project - Permissions
Resources
Read or Watch:

Permissions
man or help:
chmod
sudo
su
chown
chgrp
id
groups
whoami
adduser
useradd
addgroup
Learning Objectives
At the end of this project, you should be able to explain to anyone, without the help of Google:

Permissions:

The functions of the commands: chmod, sudo, su, chown, chgrp.
Linux file permissions and how to represent each of the three sets of permissions (owner, group, and other) as a single digit.
Methods to change permissions, owner, and group of a file.
Reasons why a normal user cannot change the owner of a file (chown).
How to run a command with root privileges.
Changing user ID or becoming superuser.

Other Man Pages:

How to create a user.
How to create a group.
How to print real and effective user and group IDs.
How to print the groups a user is in.
How to print the effective user ID.
Requirements
General
Allowed editors: vi, vim, emacs.
All scripts will be tested on Ubuntu 22.04 LTS.
All scripts must be exactly two lines long (use $ wc -l filename to confirm).
All files must end with a new line (why?).
The first line of all files should be exactly #!/bin/bash.
A README.md file at the root of the project folder, describing what each script does.
You are not allowed to use backticks, &&, ||, or ;.
All files must be executable.
Warning: tasks 3, 13, 14, 15, and 16 must be performed inside the sandbox for proper checking.

Tasks
0. My Name is Betty
Mandatory
Create a script that switches the current user to the user betty.
File: 0-iam_betty
Directory: permissions
Repo: holbertonschool-shell

1. Who Am I
Mandatory
Write a script that prints the effective username of the current user.
File: 1-who_am_i
Directory: permissions
Repo: holbertonschool-shell

2. Groups
Mandatory
Write a script that prints all the groups the current user is part of.
File: 2-groups
Directory: permissions
Repo: holbertonschool-shell

3. New Owner
Mandatory
Write a script that changes the owner of the file hello to the user betty.
File: 3-new_owner
Directory: permissions
Repo: holbertonschool-shell

4. Empty!
Mandatory
Write a script that creates an empty file called hello.
File: 4-empty
Directory: permissions
Repo: holbertonschool-shell

5. Execute
Mandatory
Write a script that adds execute permission to the owner of the file hello.
File: 5-execute
Directory: permissions
Repo: holbertonschool-shell

6. Multiple Permissions
Mandatory
Write a script that adds execute permission to the owner and the group owner, and read permission to other users, for the file hello.
File: 6-multiple_permissions
Directory: permissions
Repo: holbertonschool-shell

7. Everybody!
Mandatory
Write a script that adds execution permission to the owner, the group owner, and all other users, for the file hello.
File: 7-everybody
Directory: permissions
Repo: holbertonschool-shell

8. James Bond
Mandatory
Write a script that sets the permission for the file hello as follows:
Owner: no permission
Group: no permission
Other users: all permissions
File: 8-James_Bond
Directory: permissions
Repo: holbertonschool-shell

9. John Doe
Mandatory
Write a script that sets the mode of the file hello to -rwxr-x-wx.
File: 9-John_Doe
Directory: permissions
Repo: holbertonschool-shell

10. Look in the Mirror
Mandatory
Write a script that sets the mode of the file hello to be the same as the mode of olleh.
File: 10-mirror_permissions
Directory: permissions
Repo: holbertonschool-shell

11. Directories
Mandatory
Create a script that adds execute permission to all subdirectories of the current directory for the owner, group owner, and all other users. Regular files should remain unchanged.
File: 11-directories_permissions
Directory: permissions
Repo: holbertonschool-shell

12. More Directories
Create a script that creates a directory called my_dir with permissions 751 in the working directory.
File: 12-directory_permissions
Directory: permissions
Repo: holbertonschool-shell

13. Change Group
Write a script that changes the group owner of the file hello to school.
File: 13-change_group
Directory: permissions
Repo: holbertonschool-shell

14. Owner and Group
Write a script that changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.
File: 14-change_owner_and_group
Directory: permissions
Repo: holbertonschool-shell

15. Symbolic Links
Description: Write a script that changes the owner and the group owner of _hello to vincent and staff respectively. The file _hello is a symbolic link.
File: 15-symbolic_link_permissions
Directory: permissions
Repo: holbertonschool-shell

16. If Only
Write a script that changes the owner of the file hello to vincent only if it is owned by the user guillaume.
File: 16-if_only
Directory: permissions
Repo: holbertonschool-shell
