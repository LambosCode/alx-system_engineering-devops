#ALX SYSTEM ENGINEERING DEVOPS

**0-iam_betty changes the user ID - with su command, followed by the user.** _Note this user is supposed to be available on the system. "man su" for more details._
~~~~
1. -who_am_i prints effective useID of the current userID of the current user. using the"whoami" keword. And also be executed with "id -u -n"

2. -group This shows the group a user belongs to. "groups" keyword is used to execute the command.
 
3. -new_owner changing the owner of a file or file_owner with "chown"

4. -empty "touch" keyword is used to create any kind of file.

5. -execute "chmod u+x" creates an execute file to current user.

6. -multiple_permission aims to give all members or some member of a file or directory permissions. Doing that with "chmod ug=rw" "chmod ou+x" where u is user, o is others, g is group or groups. And lastly a for all.

7. -evrybody This script can be written using two methods. "chmod +x" performs the same operation as "chmod ugo +x" and chmod a+x. Do note script performs for excute file but can also be set for read and write (rw).

8. -James_Bond This script sets different mode permission to all its members. Binary of decimal 0 upto 7 is of three bits. which is thus then inturn used to set in the read, write and execute modes (3bits) to the three members (user, groups, others).

9. -john_Doe This helps practicalize the immediate above statement.

10. -mirror_permission this script makes use of "chmod --reference=file_inherting_from" to help inherit permission of a particular file to a new file. There's no connection or link between these two file, but the new file just take the mode permission from the inherited one.

11. -directories_permission There is a supossed directory that might contain files and other folder. so using "chmod -R" or "chmod --recursive" changes mode permission for files and folder or directiory that might be embedded.

12. -directories_permission This script helps to set mode permission while creating a directory. "mkdir -m754" the digits after the "-m" helps specifying the read, write, and executive permission belonging to either user, group and others.

13. -change_group This script can be achieved with these two syntax. "chgrp group_name filename" and "chown :group_name filename". To change the group member of a particular file.

14. -change_owner_and_group This script uses the period (.) to specify the current directory and since its a directory, ot implores -R. "chmod -R betty:holberton ."

15. -symbolic_link_permissions Must exist within the directory is a link file with the link_name _hello_ changing the group owner with a symbolic link "chown -h" helps to perfom the operation.

16. -if_only the check if a user already is existing before changing the file owner. using "chown --from" keywords.
~~~~
