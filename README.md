# simple_shell project repository

This repository contains the files for ALX **simple_shell**. It can be compiled using GCC and will execute a simple shell that can be used for some basic tasks and programs most commonly found in the /bin/ folder.

# Pre-requisites

### Authorized functions and macros:

- access (man 2 access)
- chdir (man 2 chdir)
- close (man 2 close)
- closedir (man 3 closedir)
- execve (man 2 execve)
- exit (man 3 exit)
- \_exit (man 2 \_exit)
- fflush (man 3 fflush)
- fork (man 2 fork)
- free (man 3 free)
- getcwd (man 3 getcwd)
- getline (man 3 getline)
- isatty (man 3 isatty)
- kill (man 2 kill)
- malloc (man 3 malloc)
- open (man 2 open)
- opendir (man 3 opendir)
- perror (man 3 perror)
- read (man 2 read)
- readdir (man 3 readdir)
- signal (man 2 signal)
- stat (\_\_xstat) (man 2 stat)
- lstat (\_\_lxstat) (man 2 lstat)
- fstat (\_\_fxstat) (man 2 fstat)
- strtok (man 3 strtok)
- wait (man 2 wait)
- waitpid (man 2 waitpid)
- wait3 (man 2 wait3)
- wait4 (man 2 wait4)
- write (man 2 write)

### GCC command to compile:

`gcc -Wall -Werror -Wextra -pedantic *.c -o hsh`

This wil compile all the '.c' files and change the output's name to 'hsh'.

### Template to test output:

=============
$ ./hsh

($)

hsh main.c shell.c

$ exit
$

After you clone this repository and compile the program with the command above, you will generate a file called **hsh** that can be executed by entering `./hsh` in your shell.

---

## Function Prototypes

Brief descriptions of functions contained in the project:

| Function Name   | Description                                      |
| --------------- | ------------------------------------------------ |
| \_strcmpdir     | Compares strings to find directory.              |
| find_command    | Finds command to execute in path routes.         |
| charput         | Writes the character similar to putchar.         |
| place           | Similar to puts in C.                            |
| \_strlen        | String length.                                   |
| str_concat      | Concatenates strings.                            |
| lookforslash    | Identifies if the first character is a '/'.      |
| compareExit     | Checks if the user typed 'exit'.                 |
| compareEnv      | Checks if the user typed 'env'.                  |
| execute_proc    | Executes command and args from getline.          |
| identify_string | Returns a pointer with folder address.           |
| prompt          | Infinite loop with fork to maintain the prompt.  |
| controlC        | Prevents program closure when pressing ctrl + c. |
| main            | Initializes the program.                         |

