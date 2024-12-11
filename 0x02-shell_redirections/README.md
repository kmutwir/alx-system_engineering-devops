# 0x02. Shell, I/O Redirections and filters

Bash scripts to perform tasks related to
[Input/output](https://en.wikipedia.org/wiki/Input/output)

0. [0-hello_world](./0-hello_world) - Print “Hello, World”, followed by a new
   line to the standard output.
1. [1-confused_smiley](./1-confused_smiley) - Display confused smiley `"(Ôo)'`.
2. [2-hellofile](./2-hellofile) - Display the content of the `/etc/passwd` file.
3. [3-twofiles](./3-twofiles) - Display the content of `/etc/passwd` and
   `/etc/hosts`.
4. [4-lastlines](./4-lastlines) - Display the last 10 lines of `/etc/passwd`.
5. [5-firstlines](./5-firstlines) - Display the first 10 lines of `/etc/passwd`.
6. [6-third_line](./6-third_line) - Display the third line of the file `iacta`.
7. [7-file](./7-file) - Create a file named exactly
   `\*\\'"Best School"\'\\*$\?\*\*\*\*\*:)` containing the text `Best School`
   ending by a new line.
8. [8-cwd_state](./8-cwd_state) - Redirect the ouput of the command `ls -la` to
   file `ls_cwd_content`.
9. [9-duplicate_last_line](./9-duplicate_last_line) - Duplicate the last line
   of the file `iacta`.
10. [10-no_more_js](./10-no_more_js) - Delete all the regular files
    (not the directories) with a `.js` extension that are in current directory
    and all its subfolders.
11. [11-directories](./11-directories) - Count number of **all** directories and
    sub-directories in the current directory, except parent and current
    directories.
12. [12-newest_files](./12-newest_files) - Display the 10 newest files in
    current directory, one file per line, sorted from the newest to the oldest.
13. [13-unique](./13-unique) - Print only words that appear exactly once.
    - Input format: One line, one word.
    - Output format: One line, one word.
    - Words should be sorted.
14. [14-findthatword](./14-findthatword) - Display lines containing the pattern
    `root` from the file `/etc/passwd`.
15. [15-countthatword](./15-countthatword) - Display the number of lines that
    contain the pattern `bin` in the file `/etc/passwd`.
16. [16-whatsnext](./16-whatsnext) - Display lines containing pattern `root`
    and 3 lines after them in the file `/etc/passwd`.
17. [17-hidethisword](./17-hidethisword) - Display all lines in file
    `/etc/passwd that do not contain the pattern `bin`.
18. [18-letteronly](./18-letteronly) - Display all lines of file
    `/etc/ssh/sshd_config` starting with a letter (upper and lower).
19. [19-AZ](./19-AZ) - Replace all characters `A` and `c` from input to `Z`
    and `e` respectively.
20. [20-hiago](./20-hiago) - Remove all letters `c` and `C` from input.
21. [21-reverse](./21-reverse) - Reverse the input.
