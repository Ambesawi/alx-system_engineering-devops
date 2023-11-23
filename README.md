# 0x00. Shell, Basics

## Learning Objectives

At the end of this project, you should be able to explain the following concepts without the help of Google:

### General

- **RTFM:**
  - Understanding the meaning of RTFM.

- **Shebang:**
  - Knowing what a shebang is.

- **Shell:**
  - Understanding the concept of the shell.

- **Terminal vs. Shell:**
  - Distinguishing between a terminal and a shell.

- **Shell Prompt:**
  - Understanding the shell prompt and how to use the history (the basics).

### Navigation

- **Commands & Built-ins:**
  - Knowing what the commands or built-ins `cd`, `pwd`, `ls` do.

- **Filesystem Navigation:**
  - Understanding how to navigate the filesystem.

- **Special Directories:**
  - Knowing the purpose of the `.` and `..` directories.

- **Working Directory:**
  - Understanding the working directory, how to print it, and how to change it.

- **Root Directory:**
  - Knowing what the root directory is.

- **Home Directory:**
  - Understanding the home directory and how to navigate there.

- **Hidden Files:**
  - Knowing the characteristics of hidden files and how to list them.

- **`cd -` Command:**
  - Understanding what the `cd -` command does.

### Looking Around

- **Commands:**
  - Understanding what the commands `ls`, `less`, `file` do.

- **Options and Arguments:**
  - Knowing how to use options and arguments with commands.

- **ls Long Format:**
  - Understanding the `ls` long format and how to display it.

### A Guided Tour

- **ln Command:**
  - Knowing what the `ln` command does.

- **Important Directories:**
  - Understanding the contents of the most common/important directories.

- **Symbolic Link vs. Hard Link:**
  - Knowing what a symbolic link and a hard link are.
  
- **Difference between Hard Link and Symbolic Link:**
  - Understanding the difference between a hard link and a symbolic link.

### Manipulating Files

- **Commands:**
  - Knowing what the commands `cp`, `mv`, `rm`, `mkdir` do.

- **Wildcards:**
  - Understanding what wildcards are and how they work.

- **Using Wildcards:**
  - Knowing how to use wildcards.

### Working with Commands

- **Commands:**
  - Understanding what the commands `type`, `which`, `help`, `man` do.

- **Types of Commands:**
  - Knowing the different kinds of commands.

- **Alias:**
  - Understanding what an alias is.

- **help vs. man:**
  - Knowing when to use the command `help` instead of `man`.

### Reading Man Pages

- **Reading a Man Page:**
  - Knowing how to read a man page.

- **Man Page Sections:**
  - Understanding man page sections.

- **Section Numbers:**
  - Knowing the section numbers for User commands, System calls, and Library functions.

### Keyboard Shortcuts for Bash

- **Common Shortcuts:**
  - Knowing common shortcuts for Bash.

### LTS

- **LTS:**
  - Understanding the meaning of LTS.

### Copyright - Plagiarism

You are tasked to come up with solutions for the tasks below yourself to meet the above learning objectives. You will not be able to meet the objectives of this or any following project by copying and pasting someone else’s work. You are not allowed to publish any content of this project. Any form of plagiarism is strictly forbidden and will result in removal from the program.

## Requirements

### General

- **Allowed Editors:**
  - vi, vim, emacs.

- **Testing Environment:**
  - All your scripts will be tested on Ubuntu 20.04 LTS.

- **Script Length:**
  - All your scripts should be exactly two lines long (`$ wc -l file` should print 2).

- **File Ending:**
  - All your files should end with a new line.

- **First Line:**
  - The first line of all your files should be exactly `#!/bin/bash`.

- **README.md:**
  - A `README.md` file at the root of the repo, containing a description of the repository.

- **README.md in Project Folder:**
  - A `README.md` file, at the root of the folder of this project, describing what each script is doing.

- **Restrictions:**
  - You are not allowed to use backticks, `&&`, `||` or `;`.

- **Executable Scripts:**
  - All your scripts must be executable. To make your file executable, use the `chmod` command: `chmod u+x file`.

## More Info

### Example of Line Count and First Line

```bash
julien@ubuntu:/tmp$ wc -l 12-file_type 
2 12-file_type
julien@ubuntu:/tmp$ head -n 1 12-file_type 
#!/bin/bash
julien@ubuntu:/tmp$ 
