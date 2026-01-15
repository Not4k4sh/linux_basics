# linux_basics

# Linux Basic Commands – README

## Introduction
This README provides a brief explanation of commonly used Linux commands for directory navigation, file and directory management, file viewing and editing, permission handling, and basic system monitoring. These commands are essential for beginners to understand and work efficiently in a Linux environment.

---

## Directory Navigation

- `pwd`  
  Displays the current working directory.

- `ls`  
  Lists files and directories in the current directory.  
  Options:  
  - `ls -l` shows detailed information such as permissions and file size  
  - `ls -a` includes hidden files

- `cd`  
  Changes the current directory.  
  Examples:  
  - `cd foldername`  
  - `cd ..` (move to parent directory)  
  - `cd /` (root directory)  
  - `cd ~` (home directory)

---

## Root vs Home Directory

- `/` is the root directory and the top level of the Linux file system  
- `/home/username` is the home directory for a specific user  
- `~` is a shortcut that represents the home directory

---

## Creating and Removing Files and Directories

- `mkdir`  
  Creates a new directory.  
  Example: `mkdir my_folder`

- `touch`  
  Creates an empty file.  
  Example: `touch file.txt`

- `rm`  
  Deletes files or directories.  
  Example: `rm file.txt`  
  Example (directory): `rm -r foldername`

- `rmdir`  
  Removes empty directories only.  
  Example: `rmdir empty_folder`

---

## Viewing and Editing Files

- `cat`  
  Displays the content of a file.

- `less`  
  Views file content page by page. Press `q` to quit.

- `nano`  
  A simple terminal-based text editor.

- `vim`  
  An advanced text editor commonly used in Linux systems.

---

## File Permissions and Ownership

- `ls -l`  
  Displays file permissions, ownership, and file details.

- `chmod`  
  Changes file permissions.  
  Example: `chmod 755 file.txt`

- `chown`  
  Changes file ownership (requires administrator privileges).  
  Example: `sudo chown username file.txt`

---

## System Monitoring Commands

- `top`  
  Displays running processes and system usage.

- `htop`  
  An enhanced version of `top` (if installed).

- `df -h`  
  Shows disk usage in a human-readable format.

- `free -m`  
  Displays memory usage in megabytes.

---

## Conclusion
These Linux commands form the foundation for working with the Linux operating system. Practicing them helps in understanding system structure, managing files efficiently, and monitoring system performance.
