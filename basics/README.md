# Shell Basics

This directory contains introductory Bash scripts that cover the fundamental operations of the Linux command line. These scripts are part of the ALU Shell curriculum and focus on navigation, file inspection, and basic shell logic.

## 📋 Table of Contents

| File | Description |
| :--- | :--- |
| [`0-current_working_directory`](./0-current_working_directory) | Prints the absolute path of the current working directory. |
| [`1-listit`](./1-listit) | Displays the contents of the current directory. |
| [`2-bring_me_home`](./2-bring_me_home) | Changes the working directory to the user's home directory. |
| [`3-listfiles`](./3-listfiles) | Displays current directory contents in long format. |
| [`4-listmorefiles`](./4-listmorefiles) | Displays current directory contents, including hidden files. |
| [`5-listfilesdigitonly`](./5-listfilesdigitonly) | Displays contents with user/group IDs in long format, including hidden files. |
| [`6-firstdirectory`](./6-firstdirectory) | Creates a directory named `my_first_directory` in `/tmp/`. |
| [`7-movethatfile`](./7-movethatfile) | Moves the file `betty` from `/tmp/` to `/tmp/my_first_directory`. |
| [`8-firstdelete`](./8-firstdelete) | Deletes the file `betty`. |
| [`9-firstdirdeletion`](./9-firstdirdeletion) | Deletes the directory `my_first_directory`. |
| [`10-back`](./10-back) | Changes the working directory to the previous one. |
| [`11-lists`](./11-lists) | Lists all files in the current, parent, and `/boot` directories. |
| [`12-file_type`](./12-file_type) | Prints the type of the file named `iamafile`. |
| [`13-symbolic_link`](./13-symbolic_link) | Creates a symbolic link named `__ls__` to `/bin/ls`. |
| [`14-copy_html`](./14-copy_html) | Copies all HTML files from the current directory to the parent directory. |

> **Note:** Update this table as you add new scripts. It is good practice to keep your README in sync with your code.

## 🛠️ Requirements

- **OS:** Ubuntu 20.04 LTS
- **Shell:** Bash
- **Style:** All scripts must be exactly compliant with the task instructions (line count, allowed commands, etc.)
- **Executable:** Every script must have execute permissions.

## 🚀 Usage

To make a script executable and run it:

```bash
chmod u+x ./script_name
./script_name
