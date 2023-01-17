# Commands

LINUX 

List of permissions

chmod u+x myfile - Gives the user execute permission on myfile.

chmod +x myfile - Gives everyone execute permission on myfile.

chmod ugo+x myfile - Same as the above command, but specifically specifies user, group and other.

chmod 400 myfile - Gives the user read permission, and removes all other permission. 

chmod 764 myfile - Gives user full access, group read and write access, and other read access.

chmod 751 myfile - Gives user full access, group read and execute permission, and other, execute permission.

chmod +s myfile - Set the setuid bit.

chmod go=rx myfile - Remove read and execute permissions for the group and other.
