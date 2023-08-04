Script 0-iam_betty switches the current user to user betty
Script 1-who_am_i prints the effective username of the current user
Script 2-groups prints all the groups the current user is part of
Script 3-new_owner changes the owner of the file hello to the user betty
Script 4-empty creates an empty file called hello
Script 5-execute adds execute permission to the owner of the file hello
Script 6-multiple_permissions adds execute permission to the owner and the group owner, and read permission to others, to the file hello
Script 7-everybody adds execute permission to the owner, the group owner and other users, to the file hello
Script 8-James_Bond sets all the permissions for other users only
Script 9-John_Doe sets the mode of the file hello to -rwxr-x-wx
Script 10-mirror_permissions sets the mode of the file hello the same as olleh's mode
Script 11-directories-permissions adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users
Script 12-directory_permissions creates an directory with permissions 751 in the workind directory
Script 13-change_group changes the group owner to school for the file hello
Script 100-change_owner_and_group changes the owner to vincent and the group owner to staff for all the files and directories in the working directory
Script 101-symbolic_link_permissions changes the owner and group owner for the file _hello to vincent and staff respectively
Script 102-if_only changes the owner of the file hello to betty only if it is owner by the user guillaume
