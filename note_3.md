# Git

### Version Control and Collaboration
It's a essential to use a version control system for software development and other documentation

### Changes vs. Snapshots(Git)
***
![N|solid](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*b2r3AE7UU1gCdXZg1bLykQ.png)

### Local, Centralized, and Distributed Version Control
***
**Git use distributed**
![N|solid](https://www.researchgate.net/profile/Sofia-Feist/publication/316553817/figure/fig2/AS:669480740982806@1536628055836/Centralized-Version-Control-vs-Distributed-Version-Control.ppm)

### Three States in Git
***
![N|solid](https://git-scm.com/book/en/v2/images/areas.png)

### My Git Version
```sh
User@DESKTOP-36GE0S6 MINGW64 ~
$ git --version
git version 2.42.0.windows.2
```

### Git config: First-time setup
***
- Git configurations are stored in three levels
1\) System level: **--system option**. Affects all uses and repostiories on the system(administrative)
**file:/etc/gitconfig**
2\) Global(user) level: **--global option**. Affects all repostiories of a current user
**file:~/.config/git/config**
3\) Local level: **--local option**. Specific to the current repository
**file:.git/gitconfig**
\* Each level overrides values in the previous level: **system->global->local**
    ```sh
    $ git config --list
    $ git config --list --show-origin
    ```

## Commands
***
> **$ git init: Initializing a repository in an exisiting directory**
> **$ git status: Checking repostiory status**
> **$ git add [file_name]: Adding a new file to be staged (tracked)**
> **$ git add .: Adding all files to be staged (tracked)**
> **$ git rm -cached [file_name]: Unstaging a file**
> **$ nano .gitignore: Ignoring a file**
> **$ git commit -m "commit message": Commit**
-m : recommand

### More
***
**\# ignore all .a files**
**\*.a**
**# but do track lib.a, even though you're ignoring .a files above**
**!lib.a**
**# only ignore the TODO file in the current directory, not subdir /TODO**
**/TODO**
**# ignore all files in any directory named build**
**build/**
**# ignore doc/notes.txt, but not doc/server/arch.txt**
**doc/\*.txt**
**# ignore all .pdf files in the doc/ directory and any of its subdirectories**
**doc/\*\*/\*.pdf**








