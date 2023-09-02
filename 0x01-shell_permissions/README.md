0. su betty : switches to the current user to the user betty
1. whoami : prints the effective username of the current user.
2. groups : prints all the groups the current user is part of.
3. sudo chown betty hello : changes the owner of the file hello to the user betty
4. touch hello : creates an empty file called hello
5. chmo u+x hello : adds execute permission to the owner of the file hello
6. chmod ug+x,o+r : adds execute permission to the owner and the group owner, and read permission to other users, to the file hello
7. chmod a+x hello : adds execution permission to the owner, the group owner and the other users, to the file hello
8. chmod 007 hello : sets the permission to the file hello as follows:
Owner: no permission at all
Group: no permission at all
Other users: all the permissions
9. chmod 753 hello : sets the mode of the file hello to: -rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello
10. chmod --reference=olleh hello : sets the mode of the file hello the same as olleh’s mode
11. chmod a+X * : adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.
Regular files should not be changed
12. mkdir -m 751 my_dir : creates a directory called my_dir with permissions 751 in the working directory.
13. chgrp school hello : changes the group owner to school for the file hello

