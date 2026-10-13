# PROGRAM 1 : BASIC LINUX COMMANDS

## AIM :
To familiarize students with basic Linux commands for file, directory, and system management, compare them with equivalent DOS commands, and execute them in a Linux environment.

## CONTEXT :
This C program demonstrates how to execute Linux shell commands within a C program using the system() function (provided by <stdlib.h> library). 

## SOME OF THE LINUX COMMANDS :

| Command | Function | Example |
|---|---|---|
| `pwd` | Display current working directory | `pwd` |
| `ls` | List files and directories | `ls` |
| `ls -l` | List files in long format | `ls -l` |
| `ls -a` | Show all files (including hidden files) | `ls -a` |
| `cd` | Change directory | `cd Documents` |
| `mkdir` | Create a new directory | `mkdir Demo` |
| `rmdir` | Remove an empty directory | `rmdir Demo` |
| `touch` | Create an empty file | `touch file.txt` |
| `cp` | Copy files/directories | `cp file1.txt file2.txt` |
| `mv` | Move or rename a file | `mv old.txt new.txt` |
| `rm` | Remove a file | `rm file.txt` |
| `rm -r` | Remove a directory recursively | `rm -r Demo` |
| `cat` | Display file contents | `cat notes.txt` |

## SOURCE CODE :
**File :** [exp1.c](https://github.com/112514022/osLab/blob/667d2872d6079fd68069d4f72fce1ab58d6f42a6/oslab/ex01/exp1.c)

## COMPILATION :

```bash
gcc exp1.c -o exp1
```

## EXECUTION :

```bash
./exp1
```

## OUTPUT :
![Output for Experiment 1](https://github.com/112514022/osLab/blob/56f3809c55d0aeae29c040e326dabbad7c0baa49/oslab/ex01/image.png)
