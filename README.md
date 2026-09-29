# 🐧 Linux Command-Line Essentials

**A Practical Guide to Exploring and Working with the Linux Terminal**

---

## 👋 About This Repository

The Linux command line provides a direct and efficient way to interact with the operating system. Understanding basic commands is an important foundation for Linux administration, shell programming, software development, DevOps, and cybersecurity.

This repository contains a collection of **25 essential Linux commands** practiced as part of the **Linux Administration and Shell Programming Laboratory**.

Each command is presented with its purpose, basic syntax, an example, sample output, and practical uses. The aim is to make the commands easy to understand and useful for repeated laboratory practice.

---

## 🎯 Learning Objective

The main objective of this repository is to develop practical familiarity with the Linux terminal by working with commands related to:

- System information
- User identification
- Directory navigation
- File and folder management
- Text searching and processing
- Command history
- File compression
- File permissions
- Disk usage
- Mathematical operations

---

## 📂 Command Collection

| No. | Command | Main Purpose |
|---:|---|---|
| 01 | `date` | Display system date and time |
| 02 | `who` | View currently logged-in users |
| 03 | `whoami` | Identify the current user |
| 04 | `echo` | Display text or variable values |
| 05 | `man` | Access command documentation |
| 06 | `ls` | List files and directories |
| 07 | `mkdir` | Create directories |
| 08 | `cd` | Navigate between directories |
| 09 | `rmdir` | Remove empty directories |
| 10 | `cp` | Copy files and directories |
| 11 | `mv` | Move or rename files |
| 12 | `find` | Search for files and directories |
| 13 | `history` | View previously executed commands |
| 14 | `cat` | Display file contents |
| 15 | `clear` | Clear the terminal screen |
| 16 | `cal` | Display a calendar |
| 17 | `grep` | Search for text patterns |
| 18 | `wc` | Count lines, words, and characters |
| 19 | `sort` | Arrange text data |
| 20 | `bc` | Perform calculations |
| 21 | `help` | View Bash built-in command help |
| 22 | `gzip` | Compress files |
| 23 | `chmod` | Modify file permissions |
| 24 | `df` | Check disk space |
| 25 | `pwd` | Display the current directory |

---

# 🧭 Command Categories

## 🖥️ System & User Information

Commands used to understand the current system state and user session.

- `date`
- `who`
- `whoami`
- `hostname`
- `pwd`

---

## 📁 Directory & File Management

Commands used to create, access, copy, move, and remove files and directories.

- `ls`
- `mkdir`
- `cd`
- `rmdir`
- `cp`
- `mv`
- `cat`

---

## 🔎 Searching & Text Processing

Commands that help locate files and process textual information.

- `find`
- `grep`
- `wc`
- `sort`

---

## 🧰 Terminal Utilities

Commands that improve interaction with the Linux command line.

- `echo`
- `man`
- `history`
- `clear`
- `cal`
- `help`

---

## 🔐 System Management

Commands related to permissions, storage, and file compression.

- `gzip`
- `chmod`
- `df`

---

## 🧮 Mathematical Operations

- `bc`

---

# 📚 Command Reference

## 01. `date`

### Purpose

Displays the current system date and time.

### Syntax

`date`

### Example

`date`

### Sample Output

`Thu Jul 10 11:20:15 IST 2026`

### Practical Uses

- Checking the current system time
- Generating timestamps
- Supporting time-related operations in scripts

---

## 02. `who`

### Purpose

Displays information about users currently logged into the Linux system.

### Syntax

`who`

### Example

`who`

### Sample Output

`student   pts/0   Jul 10 09:15`

### Practical Uses

- Checking active user sessions
- Monitoring logged-in users

---

## 03. `whoami`

### Purpose

Displays the username of the currently active user.

### Syntax

`whoami`

### Example

`whoami`

### Sample Output

`student`

### Practical Uses

- Identifying the current account
- Verifying the active user before performing operations

---

## 04. `echo`

### Purpose

Displays text, messages, or variable values in the terminal.

### Syntax

`echo [STRING]`

### Example

`echo "Welcome to Linux"`

### Sample Output

`Welcome to Linux`

### Practical Uses

- Printing messages
- Displaying variable values
- Producing output in shell scripts

---

## 05. `man`

### Purpose

Opens the manual documentation available for a Linux command.

### Syntax

`man <command>`

### Example

`man ls`

### Sample Output

`LS(1) User Commands`

### Practical Uses

- Learning command syntax
- Checking available options
- Accessing command documentation

---

## 06. `ls`

### Purpose

Lists the files and directories available in the current location.

### Syntax

`ls [OPTION]`

### Example

`ls -l`

### Sample Output

`Documents  Downloads  file.txt  Pictures`

### Practical Uses

- Viewing directory contents
- Checking file information
- Exploring the file system

---

## 07. `mkdir`

### Purpose

Creates a new directory at the specified location.

### Syntax

`mkdir <directory_name>`

### Example

`mkdir LinuxLab`

### Sample Output

`Directory 'LinuxLab' created successfully.`

### Practical Uses

- Creating folders
- Organizing files and project resources

---

## 08. `cd`

### Purpose

Changes the current working directory.

### Syntax

`cd <directory_path>`

### Example

`cd LinuxLab`

### Sample Output

`Current directory changed to LinuxLab`

### Practical Uses

- Moving between directories
- Accessing files stored in different locations

---

## 09. `rmdir`

### Purpose

Removes an empty directory from the file system.

### Syntax

`rmdir <directory_name>`

### Example

`rmdir LinuxLab`

### Sample Output

`Directory 'LinuxLab' removed successfully.`

### Practical Uses

- Removing unused empty folders
- Cleaning up directory structures

---

## 10. `cp`

### Purpose

Creates a copy of a file or directory while preserving the original.

### Syntax

`cp <source> <destination>`

### Example

`cp file1.txt file2.txt`

### Sample Output

`File copied successfully.`

### Practical Uses

- Creating backup copies
- Duplicating files
- Copying resources between locations

---

## 11. `mv`

### Purpose

Moves a file or directory to another location. It can also be used to rename files.

### Syntax

`mv <source> <destination>`

### Example

`mv file1.txt Documents/`

### Sample Output

`File moved successfully.`

### Practical Uses

- Moving files
- Organizing directories
- Renaming files and folders

---

## 12. `find`

### Purpose

Searches for files and directories based on specified conditions.

### Syntax

`find <path> <expression>`

### Example

`find . -name "file.txt"`

### Sample Output

`./Documents/file.txt`

### Practical Uses

- Locating files
- Searching using file names
- Finding files based on different criteria

---

## 13. `history`

### Purpose

Displays commands that were previously executed in the terminal.

### Syntax

`history`

### Example

`history`

### Sample Output

`1 ls`
`2 pwd`
`3 mkdir LinuxLab`
`4 history`

### Practical Uses

- Reviewing previous commands
- Reusing commands
- Tracking terminal activity

---

## 14. `cat`

### Purpose

Displays the contents of a text file.

### Syntax

`cat <filename>`

### Example

`cat sample.txt`

### Sample Output

`Welcome to Linux Administration Lab`

### Practical Uses

- Reading text files
- Combining file contents
- Displaying file information

---

## 15. `clear`

### Purpose

Removes previously displayed output from the terminal screen.

### Syntax

`clear`

### Example

`clear`

### Sample Output

`Terminal screen cleared`

### Practical Uses

- Keeping the terminal clean
- Improving readability while working

---

## 16. `cal`

### Purpose

Displays a calendar directly in the terminal.

### Syntax

`cal [month] [year]`

### Example

`cal`

### Sample Output

`July 2026`

### Practical Uses

- Viewing the current month's calendar
- Displaying a calendar for a particular month or year

---

## 17. `grep`

### Purpose

Searches for a specified word or pattern within text or file contents.

### Syntax

`grep <pattern> <filename>`

### Example

`grep "Linux" sample.txt`

### Sample Output

`Linux Administration Lab`

### Practical Uses

- Searching text inside files
- Filtering command output
- Locating specific information

---

## 18. `wc`

### Purpose

Counts lines, words, and characters contained in a file.

### Syntax

`wc <filename>`

### Example

`wc sample.txt`

### Sample Output

`5 18 120 sample.txt`

### Practical Uses

- Counting words and lines
- Measuring text file contents
- Performing basic text analysis

---

## 19. `sort`

### Purpose

Arranges lines of text in alphabetical or numerical order.

### Syntax

`sort <filename>`

### Example

`sort names.txt`

### Sample Output

`Alice`
`John`
`Kevin`
`Mary`

### Practical Uses

- Organizing text data
- Sorting names or values
- Preparing data for further processing

---

## 20. `bc`

### Purpose

Provides a command-line calculator for performing arithmetic operations.

### Syntax

`bc`

### Example

`echo "25+15" | bc`

### Sample Output

`40`

### Practical Uses

- Performing calculations
- Evaluating arithmetic expressions
- Supporting mathematical operations in shell scripts

---

## 21. `help`

### Purpose

Provides information about Bash built-in commands.

### Syntax

`help [command]`

### Example

`help cd`

### Sample Output

`cd: cd [-L|-P] [dir]`
`Change the shell working directory.`

### Practical Uses

- Learning Bash built-in commands
- Checking command syntax
- Accessing help directly from the terminal

---

## 22. `gzip`

### Purpose

Compresses files to reduce their storage size.

### Syntax

`gzip <filename>`

### Example

`gzip report.txt`

### Sample Output

`report.txt.gz`

### Practical Uses

- Reducing file size
- Saving storage space
- Preparing files for transfer

---

## 23. `chmod`

### Purpose

Changes the permissions assigned to files and directories.

### Syntax

`chmod <permissions> <filename>`

### Example

`chmod 755 script.sh`

### Sample Output

`Permissions of 'script.sh' changed successfully.`

### Practical Uses

- Controlling file access
- Setting read, write, and execute permissions
- Making shell scripts executable

---

## 24. `df`

### Purpose

Displays information about used and available disk space on mounted file systems.

### Syntax

`df -h`

### Example

`df -h`

### Sample Output

`Filesystem      Size  Used Avail Use%`
`/dev/sda1        50G   20G   28G  42%`

### Practical Uses

- Monitoring available storage
- Checking disk usage
- Identifying storage limitations

---

## 25. `pwd`

### Purpose

Displays the complete path of the current working directory.

### Syntax

`pwd`

### Example

`pwd`

### Sample Output

`/home/student/LinuxLab`

### Practical Uses

- Identifying the current location
- Verifying the working directory
- Avoiding file-operation errors

---

# 🧠 Skills Practiced

Through these commands, the following practical skills are developed:

- Navigating the Linux file system
- Managing files and directories
- Identifying users and system information
- Searching and filtering text
- Reading and processing files
- Working with file permissions
- Managing disk space
- Compressing files
- Performing command-line calculations
- Using built-in Linux documentation

---

# 📌 Key Takeaways

The Linux terminal provides powerful tools for interacting directly with the operating system.

Practicing these 25 commands builds a foundation for more advanced areas such as:

- Shell Scripting
- Linux System Administration
- DevOps
- Cloud Computing
- Cybersecurity
- Server Management

Regular command-line practice helps improve both Linux familiarity and problem-solving skills.

---

# 📚 References

- Linux Manual Pages using `man`
- GNU Bash Documentation
- Ubuntu Documentation
- Linux Foundation Documentation

---

## 👩‍💻 Author

**KRITHIKA UMASANKAR**

B.E. Computer Science and Engineering  
Mepco Schlenk Engineering College

*Linux Administration & Shell Programming Laboratory*

---

⭐ If this repository is useful for your Linux learning journey, feel free to explore the commands and practice them in your own environment.

**Keep Learning. Keep Practicing. 🐧**
