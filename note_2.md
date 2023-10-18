# Shell Scirpt - [Git Bash](https://git-scm.com/)

### shell script declaration
#!/bin/sh must be declared at the top of the file (test.sh).

## I/O Redirection: Standard ( OUTPUT / INPUT )
***
- By default, standard output is screen
- **">"** after a command(e.g, ls) to create and save the output in a file.
- **"<"** redirect input from a file using.
- **"cat"** displays the content of a text file.
- **">>"** appends output to an estising file or create and write to a new file if it doesn't exist.
- Can mix "<"and">" togetehr in a single line.

## Commands
***
> Pipelines "|": pipeline feeds output of previous command to input of next command.
>  \+ press "q" key to exit the screen.
> \+ $ ls | wc -l: number of files.
> Expansion "echo (*/~)": special characters expand its meaning when given to shell commands.
> \+ echo *: looks like ls.
> \+ echo ~: current users home directory.
> Backslash "\": backslash can be used to ignore line change in command ("enter"), to enter a long command in multiple lines.

## Important
***
#### Permissions
- Linux is a multi-user system.
- Files and dirctories hav a permission assigned differently to owner / group / others.

**[me@linuxbox me]$ ls -l /bin/bash**
**-rwxr-xr-x 1 root root 1113504 Jun  6  2019 /bin/bash**
**first root: user ID**
**second root: group**
**r : read**
**w : write**
**x : execute**
![N|solid](https://linuxcommand.org/images/file_permissions.png)


## More
***
***Special variable***
| variable | function |
| ------ | ------ |
| $0 | Script Name. |
| $1~$9 | Argument value to be handed over a the time of shell script execution. |
| $# | Number of arguments passed in the script. |
| $* | Collect all arguments and treat them as one. |
| $@ | Process all arguments separately. |
| $$ | Process ID for this shell script. |
| $? | End value of the previously executed command (0: success, 1: failure). |
| $!? | Background process ID last executed. |

***Substituting variable***
| grammer | explandation |
| ----- | ----- |
| $name or ${name} |  Replace corresponding variable values. |
| ${name:=andrew} | If the variable is not yet set or if it is blank string, return andrew, and save the name variable. |
| ${name:+andrew} | Returns andrew if the variable is not set, and is not stored in the name variable. |
| ${name:?andrew} | If there is no name value, the conversion fails and displays an error. |







