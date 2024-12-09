# 0x01. Shell, permissions

> [home](../README.md)

Bash scripts that perform tasks related to user permissions.

0. [0-iam_betty](./0-iam_betty) - Switch the current user to the user `betty`.
1. [1-who_am_i](./1-who_am_i) - Print the effective username of the current
   user.
2. [2-groups](./2-groups) - Print all the groups the current user is part of.
3. [3-new_owner](./3-new_owner) - Change owner of file `hello` to the user
   `betty`.
4. [4-empty](./4-empty) - Create an empty file called `hello`.
5. [5-execute](./5-execute) - Add execute permission to owner of file `hello`.
6. [6-multiple_permissions](./6-multiple_permissions) - Add execute permission
   to owner and group owner, and read permission to other users, to file
   `hello`.
7. [7-everybody](./7-everybody) - Add execution permission to owner, group owner
   and other users, for the file `hello`
8. [8-James_Bond](./8-James_Bond) - Set permission to file `hello` as follows:
   - Owner: no permission at all
   - Group: no permission at all
   - Other users: all the permissions
9. [9-John_Doe](./9-John_Doe) - Set the mode of the file hello to `-rwxr-x-wx`
10. [10-mirror_permissions](./10-mirror_permissions) - Set the mode of file
    `hello` the same as `olleh`’s mode.
11. [11-directories_permissions](./11-directories_permissions) - Add execute
    permission to all subdirectories of current directory for owner, group owner
    and all other users. Regular files should not be changed.
12. [12-directory_permissions](./12-directory_permissions) - Create a directory
    ` my_dir` with permissions `751` in the working directory.
13. [13-change_group](./13-change_group) - Change group owner to `school` for
    the file `hello`.
