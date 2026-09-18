# Permissions

This directory contains shell scripts for managing file permissions and users.

## Scripts

- '0-iam_betty': Changes the current user to the user betty.
- '1-who_am_i': Prints the effective username of the current user.
- '2-groups': Prints all the groups the current user is part of.
- '3-new_owner': Changes the owner of the file hello to the user betty
- '4-empty': Creates an empty file called hello.
- '5-execute': Adds execute permission to the owner of the file hello.
- '6-multiple_permissions': Adds execute permission to the owner and the group owner, and read permission to the users, to the file hello.
- '7-everybody': Adds execute permission to the owner, the group owner and the other users, to the file hello.
- '8-James_Bond': Sets the permissions of the file hello to 007 (no permissions for owner and group, all to others)
- '9-John_Doe': Sets the mode of the file hello to -rwxr-x-wx.
- '10-mirror_permissions': Sets the mode of the file hello the same as olleh's mode.
- '11-directories_permissions': Adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users, without changing regular files.
- '12-directory_permissions': Creates a directory called my_dir with permissions 751 in the working directory.      
