# 0x00. Shell, basics

> [home](../README.md)

Bash scripts to perform basic shell commands

0. [0-current_working_directory](./0-current_working_directory) - Print the
absolute path name of the current working directory.
1. [1-listit](./1-listit) - Display the contents list of current directory.
2. [2-bring_me_home](./2-bring_me_home) - Change the working directory to
   user’s home directory.
3. [3-listfiles](./3-listfiles) - Display current directory contents in long
   format.
4. [4-listmorefiles](./4-listmorefiles) - Display current directory contents
   including hidden files (starting with `.`) using long format.
5. [5-listfilesdigitonly](./5-listfilesdigitonly) - Display **all** current
   directory contents in long format with user and group IDs displayed
   numerically.
6. [6-firstdirectory](./6-firstdirectory) - Create directory
   `my_first_directory` inside `/tmp/` directory.
7. [7-movethatfile](./7-movethatfile) - Move the file `betty` from `/tmp/`
   to `/tmp/my_first_directory`.
8. [8-firstdelete](./8-firstdelete) - Delete the file betty located inside
   `/tmp/my_first_directory`
9. [9-firstdirdeletion](./9-firstdirdeletion) - Delete directory
   `my_first_directory` that is inside `/tmp` directory.
10. [10-back](./10-back) - Change working directory to the previous one.
11. [11-lists](./11-lists) - List **all** files in current directory
    the parent of the working directory and the `/boot` directory
    (in this order), in long format.
12. [12-file_type](./12-file_type) - Print the type of the file `iamafile`
    located in the `/tmp` directory.
13. [13-symbolic_link](./13-symbolic_link) - Create a symbolic link to `/bin/ls`
    named `__ls__`.
14. [14-copy_html](./14-copy_html) - Copy all the HTML files from current
    working directory to its parent, but only copy files that did not exist
    or were newer than the versions in the parent.
15. [100-lets_move](./100-lets_move) - Move all files beginning with uppercase
    letter to directory `/tmp/u`.
16. [101-clean_emacs](./101-clean_emacs) - Delete all files in current working
    directory that end with character `~`.
17. [102-tree](./102-tree) - Create directories `welcome/`, `welcome/to/`
    and `welcome/to/school` in the current directory.
18. [103-commas](./103-commas) - List **all** files and directories in current
    directory separated by commas, end directory's names with a `/`, sort the
    listing alphabetically with `.` and `..` coming first. End the listing
    with a new line
19. [school.mgc](./school_fragment_magic_file) - Create a magic file `school.mgc` that can be
    used with the command `file` to detect `School data` files. School data
    files always contain the string `SCHOOL` at offset 0.
