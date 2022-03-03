Use `whoami` to write script that prints the effective username of the current user

Use `su betty` to create a script that switches the current user to the user betty

Use `group` to write a script that prints all groups the current user is part of

Use `chown betty hello` to write a script that changes the owner of the file hello to the user betty

Use `touch hello` to write a script that creates an empty file called hello

Use `chmod u+x hello` to adds execute permission to the owner of the file hello

Use `chmod ug+x, o+r hello` to adds execute permission to the owner and group owner, and read permission to other users, to the file hello

Use `chmod a+x hello` to adds execution permission to the owner, the group owner and the other users, to the file hello

Use `chmod 007 hello` to sets the permission to the file hello as Owner, Group and Other users.

Use `chmod 753 hello` to sets the mode of the file hello 

Use `chmod --reference=olleh hello` sets the mode of the file hello the same as olleh's mode

Use `chmod a+X *` to adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users

Use `mkdir -m 751 my_dir` to creates a directory called my_dir with permissions 751 in the working directory

Use `chgrp school hello` script that changes group owner to school for the file hello

Use `chown vincent:staff *` to write a script that changes the owner to vicent and the group owner staff for all the files and directories in the working directory

Use `chmod -h vincent:staff -hello` write a script that changes the owner and group owner of -hello to vicent and staff

Use `chown --from=guillaume betty hello` to write script that changes the owner of the file hello to betty only if it is owned by the user guillaume
