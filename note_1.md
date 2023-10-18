# Shell commands - [Git Bash](https://git-scm.com/)

## Commands
***
>pwd: shows the current path in a hierarchical directory
> cd: change directory
> ls: list files and directories
> mv: move the directory or rename
> cp: copy files and directories
> more: filter for paging through text one screenful at time
> cat: concatenate the file
> less: viewing the files instead of opening the file
> tail: Used to print the last N-1 lines of a file(default value is 10)
> mkdir: create a directory if not already exist
> rm: remove files or directories
> touch: create or update a file
> grep: search for the specified text in a file  

## agruments
***
**/ : root**
**.. : upper-level** 
**~ : home of current user**
**/[directory name]: absolute path**
**./[directory name]: relative path**
**../[dirctory name]: relative path**

## More
***
***Commands***
| Command | Result |
| ------ | ------ |
| ls | List the files in the working directory |
| ls /bin | List the files in the /bin directory(or any other direcotry we care to specify) |
| ls -l | List the files in the working directory in long format |
| ls -la | List the files in the /bin direcotry and the /etc directory in long format |
| cp file1 file2 | Copies the contents of file1 into file2. If file2 does not exist, it is created; other wise, file 2 is silently overwritten with the contents of file1. |

***Wildcards Character***
| Pattern | Maches |
| ----- | ----- |
| * |  All filenames |
| g* | All filenames that begin with the character "g" |
| Data??? | Any filename that begins with the characters "Data" followed by exactly 3 more characters |
| b*.txt | All file names that begin with the character "b" and with the characters ".txt" |

## Filesystem hierarchy
***
**standard Unix filesystem.**
[![N|Solid](https://swcarpentry.github.io/shell-novice/fig/standard-filesystem-hierarchy.svg)](https://nodesource.com/products/nsolid)






