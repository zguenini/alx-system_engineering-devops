# 0x02 Shell, I/O Redirections and Filters

## Resources

- [I/O Redirection](http://linuxcommand.org/lc3_lts0070.php).
- [SpecialCharacters](http://mywiki.wooledge.org/BashGuide/SpecialCharacters).

## Tasks

0. [Hello World](./0-hello_world) : Write a script that prints `Hello, World`, followed by a new line to the standard output.
1. [Confused smiley](./1-confused_smiley) : Write a script that displays a confused smiley: `"(Ôo)'`.
2. [Let's display a file](./2-hellofile) : Displays the content of the `/etc/passwd` file.
3. [What about 2?](./3-twofiles) : Displays content of `/etc/passwd` and `/etc/hosts`.
4. [Last lines of a file](./4-lastlines) : Displays the last 10 lines of `/etc/passwd`.
5. [I'd prefer the first ones actually](./5-firstlines) : Displays the first 10 lines of `etc/passwd`.
6. [Line #2](./6-third_line) : Write a script that displays the third line of the file `iacta`.
   - The file `iacta` will be in the working directory. 
   - you are not allowed to use `sed`.
7. [It is a good file that cuts iron without making a noise](./7-file) : Write a shell script that creates a file named exactly `\*\\'"Best School"\'\\*$\?\*\*\*\*\*:)` containing the text `Best School` ending by a new line.
8. [Save current state of directory](./8-cwd_state) : Write a script that writes into the file `ls_cwd_content` the result of the command `ls -la`. If the file `ls_cwd_content` already exists, it should be overwritten. If the file `ls_cwd_content`does not exist, create it.
9. [Duplicate last line](./9-duplicate_last_line) : Write a script that duplicates the last line of the file `iacta`.
10. [No more javascript](./10-no_more_js) : Write a script that deletes all the regular files (not the directories) with a `.js` extension that are present in the current directory and all its subfolders.
11. [Don't just count your directories, make your directories count](./11-directories) : A script that counts the number of directories and sub-directories in the current directory.
    - The current and present directories should not be taken into account.
    - Hidden directories should be counted.
12. [Whats12's new](./12-newest_files) : Create a script that prints the 10 newest files in the current directory.
    - The output should be; one file per line.
    - sorted from the newest to the oldest.
13. [Being unique is better than being perfect](./13-unique) : Create a script that takes a list of words as input and prints only words that appear exactly once.
    - Input format: One line, one word.
    - Output format: One line, one word.
    - Words should be sorted.
14. [It must be in that file](./14-findthatword) : Display lines containing the pattern `"root"` from the file `/etc/passwd`.
15. [Count that word](./15-countthatword) : Displays the number of lines that contain the pattern `"bin"` in the file `/etc/passwd`.
16. [What's next?](./16-whatsnext) : Display lines containing the pattern `"root"` and 3 lines after them in the file `/etc/passwd`.
17. [I hate bins](./17-hidethisword) : Displays all the lines in the file `/etc/passwd` that do not contain the pattern `"bin"`.
18. [Letters only please](./18-letteronly) : Displays all lines of the file `/ect/ssh/sshd_config` starting with a letter.
    - include capital letters as well.
19. [A to Z](./19-AZ) : Replace all characters `A` and `c` from input to `Z` and `e` respectively.
20. [Without C, you would live in hiago](./20-hiago) : Create a script that removes all letters `c` and `C` from input.
21. [esreveR](./21-reverse) : Write a script that reverse its input.
22. [DJ Cut Killer](./22-users_and_homes) : Write a scipt that displays all users and their home directories, sorted by users, based on the `/etc/passwd` file.
23. [Empty casks make the most noise](./100-empty_casks) : Write a command that finds all empty files and directories in the current directory and all sub-directories.
    - Only names of the files and directories should be displayed (not the entire path.)
    - Hidden files should be listed also.
    - one file name per line.
    - the listing should end with a new line.
    - You are not allowed to use `basename`, `grep`, `egrep`, `fgrep` or `rgrep`.
24. [A gif is worth ten thousand words](./101-gifs) : Write a script that lists all the files with a `.gif` extension in the current directory and all its sub-directories.
    - Hidden files should be listed.
    - Only regular files (not directories) should be listed.  
    - The names of the files should be displayed without their extensions. 
    - The files should be sorted by byte values, but case-insensitive (file `aaa` should be listed before file `bbb`, file `.b` should be listed before file `a`, and file `Rona` should be listed after file `jay`) 
    - One file name per line. 
    - The listing should end with a new line. 
    - You are not allowed to use `basename`, `grep`, `egrep`, `fgrep` or `rgrep`. 
25. [Acrostic](./102-acrostic) : An acrostic is a poem (or other form of writing) in which the first letter (or syllable, or word) of each line (or paragraph, or other recurring feature in the text) spells out a word, message or the alphabet. The word comes from the French acrostiche from post-classical Latin acrostichis). As a form of constrained writing, an acrostic can be used as a mnemonic device to aid memory retrieval. [Read more](https://en.wikipedia.org/wiki/Acrostic).
* Create a script that decodes acrostics that use the first letter of each line.
    - The **‘decoded’** message has to end with a new line.
    - You are not allowed to use `grep`, `egrep`, `fgrep` or `rgrep`.
26. [The biggest fan](./103-the_biggest_fan) : Write a script that parses web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests.
    - Order by number of requests, most active host or IP at the top.
    - You are not allowed to use `grep`, `egrep`, `fgrep` or `rgrep`.
