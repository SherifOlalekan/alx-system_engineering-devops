0. su betty - switces the current user to the user betty\
1. whoami - prints the effective username of the current user\
2. id - print information about the specific user and it groups\
3. sudo chown betty hello - change the owner of the file hello to betty\
4. touch hello - creates an empty file called hello\
5. chmod u+x hello - add execute permission to the owner of the file hello\
6. chmod ug+x,o+r  hello - add execute permission to the owner and the group owner, and read permission to other users, to the file hello\
7. chmod a+x hello - adds execution permission to the owner, the group and other users to the hello file\
8. chmod 007 hello - grant no permission to the owner and group, but grant all permission to others, in the hello file\
9. chmod 753 hello - grant all permission to the owner, grant read and execute permission to the groups and grant write and execute permission to the others, in the hello file\
10. chmod --reference=olleh hell0 - sets the mode of file hello the same as olleh's\
11. chmod -R a+X * - it adds execute permission to all subdirectories for the owner, group and other users\
12. mkdir -m 751 my_dir - create a directory with specified permission in the current directory\
13. sudo chgrp school hello - chnge the group owner of hello to school\
14. chown vincent:staff * - change the owner and group for all files and directories in the current folder to the specifiedrespectively\
15. chown -h vincent:staff _hello - change the owner and group of _hello to the specified\
16. chown --from=guillaume betty hello - will change the owner of hello to betty only if it is own by guillaume first\
17. telnet towel.blinkenlights.nl - to play star wars iv episode in terminal\
