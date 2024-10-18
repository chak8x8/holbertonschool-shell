# Shell Scripting Tasks

This repository contains various shell scripting tasks aimed at improving my understanding of shell scripting, file manipulation, and system commands.

## Tasks Overview

### 0. Hello World
- **Script Name:** `0-hello_world`
- **Description:** Writes a script that prints “Hello, World”, followed by a new line to the standard output.

### 1. Confused smiley
- **Script Name:** `1-confused_smiley`
- **Description:** Displays a confused smiley "(Ôo)'".

### 2. Let's display a file
- **Script Name:** `2-hellofile`
- **Description:** Displays the content of the `/etc/passwd` file.

### 3. What about 2?
- **Script Name:** `3-twofiles`
- **Description:** Displays the content of `/etc/passwd` and `/etc/hosts`.

### 4. Last lines of a file
- **Script Name:** `4-lastlines`
- **Description:** Displays the last 10 lines of `/etc/passwd`.

### 5. I'd prefer the first ones actually
- **Script Name:** `5-firstlines`
- **Description:** Displays the first 10 lines of `/etc/passwd`.

### 6. Line #2
- **Script Name:** `6-third_line`
- **Description:** Displays the third line of the file `iacta`, which is in the working directory, without using `sed`.

### 7. It is a good file that cuts iron without making a noise
- **Script Name:** `7-file`
- **Description:** Creates a file named exactly `*\\'"Best School"'\\*$?*****:)` containing the text `Best School` ending with a new line.

### 8. Save current state of directory
- **Script Name:** `8-cwd_state`
- **Description:** Writes into the file `ls_cwd_content` the result of the command `ls -la`. If the file exists, it is overwritten; if not, it is created.

### 9. Duplicate last line
- **Script Name:** `9-duplicate_last_line`
- **Description:** Duplicates the last line of the file `iacta`, which is in the working directory.

### 10. No more javascript
- **Script Name:** `10-no_more_js`
- **Description:** Deletes all regular files (not directories) with a `.js` extension present in the current directory and all its subfolders.

### 11. Don't just count your directories, make your directories count
- **Script Name:** `11-directories`
- **Description:** Counts the number of directories and sub-directories in the current directory, excluding the current and parent directories but including hidden ones.

### 12. What’s new
- **Script Name:** `12-newest_files`
- **Description:** Displays the 10 newest files in the current directory, one file per line, sorted from newest to oldest.

### 13. Being unique is better than being perfect
- **Script Name:** `13-unique`
- **Description:** Takes a list of words as input and prints only those that appear exactly once, sorted and with one word per line.

### 14. It must be in that file
- **Script Name:** `14-findthatword`
- **Description:** Displays lines containing the pattern “root” from the file `/etc/passwd`.

### 15. Count that word
- **Script Name:** `15-countthatword`
- **Description:** Displays the number of lines that contain the pattern “bin” in the file `/etc/passwd`.

### 16. What's next?
- **Script Name:** `16-whatsnext`
- **Description:** Displays lines containing the pattern “root” and the following 3 lines in the file `/etc/passwd`.

### 17. I hate bins
- **Script Name:** `17-hidethisword`
- **Description:** Displays all lines in the file `/etc/passwd` that do not contain the pattern “bin”.

### 18. Letters only please
- **Script Name:** `18-letteronly`
- **Description:** Displays all lines of the file `/etc/ssh/sshd_config` that start with a letter, including capital letters.

### 19. A to Z
- **Script Name:** `19-AZ`
- **Description:** Replaces all characters `A` and `c` from input to `Z` and `e`, respectively.

### 20. Without C, you would live in hiago
- **Script Name:** `20-hiago`
- **Description:** Removes all letters `c` and `C` from input.

### 21. esreveR
- **Script Name:** `21-reverse`
- **Description:** Reverses its input.

### 22. DJ Cut Killer
- **Script Name:** `22-users_and_homes`
- **Description:** Displays all users and their home directories, sorted by users, based on the `/etc/passwd` file.

