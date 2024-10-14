# Holberton Shell Project

This repository contains a series of scripts that demonstrate basic shell commands and scripting in Bash. The scripts are organized in the `basics` directory and cover various tasks, including file manipulation and directory management.

## Scripts Overview

### 0-current_working_directory
- **Description**: Prints the absolute path name of the current working directory.
- **Usage**: `./0-current_working_directory`

### 1-listit
- **Description**: Displays the contents list of the current directory.
- **Usage**: `./1-listit`

### 2-bring_me_home
- **Description**: Changes the working directory to the user’s home directory.
- **Usage**: `./2-bring_me_home`

### 3-listfiles
- **Description**: Displays current directory contents in a long format.
- **Usage**: `./3-listfiles`

### 4-listmorefiles
- **Description**: Displays current directory contents, including hidden files, in a long format.
- **Usage**: `./4-listmorefiles`

### 5-listfilesnumericids
- **Description**: Displays current directory contents in a long format with user and group IDs displayed numerically, including hidden files.
- **Usage**: `./5-listfilesnumericids`

### 6-firstdirectory
- **Description**: Creates a directory named `my_first_directory` in the `/tmp/` directory.
- **Usage**: `./6-firstdirectory`

### 7-movethatfile
- **Description**: Moves the file `betty` from `/tmp/` to `/tmp/my_first_directory`.
- **Usage**: `./7-movethatfile`

### 8-rmbetty
- **Description**: Deletes the file `betty` located in `/tmp/my_first_directory`.
- **Usage**: `./8-rmbetty`

### 9-rmdir
- **Description**: Deletes the directory `my_first_directory` located in the `/tmp/` directory.
- **Usage**: `./9-rmdir`

### 10-change_directory
- **Description**: Changes the working directory to the previous one.
- **Usage**: `./10-change_directory`

### 11-ls
- **Description**: Lists all files (including hidden ones) in the current directory, the parent directory, and the `/boot` directory, in long format.
- **Usage**: `./11-ls`

### 12-file_type
- **Description**: Prints the type of the file named `iamafile` located in the `/tmp/` directory.
- **Usage**: `./12-file_type`

### 13-symbolic_link
- **Description**: Creates a symbolic link to `/bin/ls`, named `__ls__`, in the current working directory.
- **Usage**: `./13-symbolic_link`

### 14-html
- **Description**: Copies all HTML files from the current working directory to the parent directory, only if they do not exist or are newer than the versions in the parent directory.
- **Usage**: `./14-html`

### 15-uppercase
- **Description**: Moves all files beginning with an uppercase letter to the `/tmp/u` directory.
- **Usage**: `./15-uppercase`

### 16-delete
- **Description**: Deletes all files in the current working directory that end with the character `~`.
- **Usage**: `./16-delete`

### 17-create_welcome
- **Description**: Creates the directories `welcome/`, `welcome/to/`, and `welcome/to/school/` in the current directory.
- **Usage**: `./17-create_welcome`

## Requirements

- Allowed editors: vi, vim, emacs
- All scripts are tested on Ubuntu 22.04 LTS
- Each script must be exactly two lines long (use `wc -l file` to confirm)
- Each file must end with a new line
- The first line of all scripts must be exactly `#!/bin/bash`
- A `README.md` file at the root of the repository contains a description of the repository and each script
- You are not allowed to use backticks, `&&`, `||`, or `;`
- All scripts must be executable. Use the command: `chmod u+x file` to make a file executable.

## How to Run the Scripts

To execute a script, navigate to the `basics` directory and run the script using:

```bash
./script_name

