# 0x02. Shell, I/O Redirections and filters

## Tasks

* **0. Hello World**
  * [0-hello_world](./0-hello_world): a script that prints "Hello, World"  followed by a new line to the standard output.

* **1. Confused smiley**
  * [1-confused_smiley](./1-confused_smiley): a script that displays a confused smiley  `"(Ôo)'`.

* **2. Let's display a file**
  * [2-hellofile](./2-hellofile): displays the content of the  `/etc/passwd` file.

* **3. What about 2?**
  * [3-twofiles](./3-twofiles): displays the content of  `etc/passwd` and `/etc/hosts`.

* **4. Last lines of a file**
  * [4-lastlines](./4-lastlines): displays the last 10 lines of `/etc/passwd`.

* **5. I'd prefer the first ones actually**
  * [5-firstlines](./5-firstlines): displays the first 10 lines  of `/etc/passwd`.

* **6. Line #2**
  * [6-third_line](./6-third_line): a script that displays the third line  of the file `iacta`.

* **7. It is a good file that cuts iron without making a noise**
  * [7-file](./7-file): a shell script that creates a file named exactly  `\*\\'"Best School"\'\\*$\?\*\*\*\*\*:)` containing the text  `Best School` ending by a new line.

* **8. Save current state of directory**
  * [8-cwd_state](./8-cwd_state): a script that writes into the file `ls_cwd_content` the  result of the command `ls -la`.

* **9. Duplicate last line**
  * [9-duplicate_last_line](./9-duplicate_last_line): a script that duplicates the last  line of the file `iacta`.

* **10. No more javascript**
  * [10-no_more_js](./10-no_more_js): a script that deletes all the regular files (not  directories) with a `.js` extension that are present in the current directory  and all its subfolders.

* **11. Don't just count your directories, make your directories count**
  * [11-directories](./11-directories): a script that counts the number of directories and  sub-directories in the current directory, not including the current and parent  directories but counting hidden ones.

* **12. What’s new**
  * [12-newest_file](./12-newest_files): a script that displays the 10 newest files in the  current directory, one file per line, sorted from newest to oldest.

* **13. Being unique is better than being perfect**
  * [13-unique](./13-unique): a script that takes a list of words as input and only  prints words that appear exactly once, one word per line, sorted.

* **14. It must be in that file**
  * [14-findthatword](./14-findthatword): a script that displays lines containing  the pattern "root" from the file `/etc/passwd`.

* **15. Count that word**
  * [15-countthatword](./15-countthatword): a script that displays the number of lines  containing the pattern "bin" in the file `/etc/passwd`.

* **16. What's next?**
  * [16-whatsnext](./16-whatsnext): a script that displays lines containing the pattern  "root" and 3 lines after them in the file `/etc/passwd`.

* **17. I hate bins**
  * [17-hidethisword](./17-hidethisword): displays all lines in the file  `/etc/passwd` that do not contain the pattern "bin".

* **18. Letters only please**
  * [18-letteronly](./18-letteronly): displays all lines of the file  `/etc/ssh/sshd_config` starting with a letter, including capital letters.

* **19. A to Z**
  * [19-AZ](./19-AZ): a script that replaces all characters `A` and `c` from input  to `Z` and `e` respectively.

* **20. Without C, you would live in hiago**
  * [20-hiago](./20-hiago): a script that removes all letters `c` and `C` from input.

* **21. esreveR**
  * [21-reverse](./21-reverse): a script that reverses its input.

* **22. DJ Cut Killer**
  * [22-users_and_homes](./22-users_and_homes): a script that displays all users and  their home directories, sorted by users, based on the `/etc/passwd` file.

* **23. Empty casks make the most noise**
  * [100-empty_casks](./100-empty_casks): a script that finds all empty files  and directories in the current directory and all sub-directories as follows:
    * Only the names of the files and directories are displayed.
    * Hidden files included.
    * One file name per line.

* **24. A gif is worth ten thousand words**
  * [101-gifs](./101-gifs): a script that lists all the files with a `.gif` extension  in the current directory and all its sub-directories as follows:
    * Hidden files included.
    * Only regular files (not directories) listed.
    * File names displayed without extensions.
    * Files sorted by byte values, but case insensitive.
    * One file name per line.

* **25. Acrostic**
  * [102-acrostic](./102-acrostic): a script that decodes acrostics that use the first  letter of each line.

* **26. The biggest fan**
  * [103-the_biggest_fan](./103-the_biggest_fan): a script that parses web  server logs in TSV format as input and displays the 11 hosts or IP addresses  which did the most requests.
    * Ordered by number of requests, with most active hosts or IP's at the top.
