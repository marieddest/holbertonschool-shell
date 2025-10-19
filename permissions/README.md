 HEAD
# Shell permissions

## 0-iam_betty

This script switches the current user to the user `betty`.
1-who_am_i: prints the effective username of the current user
2-groups: prints all the groups the current user is part of
3-new_owner: changes the owner of the file 'hello' to the user 'betty'
3-new_owner: changes the owner of the file 'hello' to the user 'betty'
3-new_owner: changes the owner of the file 'hello' to the user 'betty'
4-empty: creates an empty file called 'hello'
5-execute: adds execute permission to the owner of the file 'hello'
6-multiple_permissions: adds execute permission to owner and group, and read permission to others for the file 'hello'
7-everybody: adds execute permission to owner, group, and others for the file 'hello'
8-James_Bond: sets permissions of file 'hello' so owner and group have none, others have all
9-John_Doe: sets permissions of file 'hello' to -rwxr-x-wx (owner: rwx, group: r-x, others: -wx)
10-mirror_permissions: sets the mode of 'hello' to be the same as 'olleh'
11-directories_permissions: adds execute permission to all subdirectories of the current directory for owner, group, and others (regular files unchanged)
12-directory_permissions: creates a directory called 'my_dir' with permissions 751 in the working directory
13-change_group: changes the group owner of the file 'hello' to 'school'
14-change_owner_and_group: changes the owner to 'vincent' and group to 'staff' for all files and directories in the working directory
15-symbolic_link_permissions: changes the owner and group of the symbolic link '_hello' to vincent and staff respectively
16-if_only: changes the owner of 'hello' to vincent only if it is currently owned by guillaume
