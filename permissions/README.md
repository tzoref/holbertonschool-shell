# Shell Permissions
0-iam_betty: Switches the current user to betty.
1-who_am_i: Prints the effective username of the current user.
2-groups: Prints all the groups the current user is part of.
3-new_owner: Changes the owner of the file hello to the user betty.
4-empty: Creates an empty file called hello.
5-execute: Adds execute permission for the owner of hello.
6-multiple_permissions: Adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
7-everybody: Adds execution permission to the owner, the group owner and the other users, to the file hello.
8-James_Bond: Sets hello permissions to 007 (no permissions for owner or group; full permissions for others).
9-John_Doe: Sets hello permissions to 753.
10-mirror_permissions: Sets the mode of the file hello the same as olleh.
11-directories_permissions: Adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.
12-directory_permissions: Creates a directory named my_dir with permissions 751.
13-change_group: Changes the group owner of the file hello to school.
14-change_owner_and_group: Changes owner and group to vincent and staff.
15-symbolic_link_permissions: Changes the owner and the group owner of symbolic link `_`hello to vincent and staff.
16-if_only: Changes the owner of the file hello to vincent only if it is owned by the user guillaume.
