# Git Commands
If you see something like `<some-content-here>` it means, that you have to 
extend the command with your own specific input.  
For example:  
`git help <command>` in table &rarr; `git help status` in your terminal.

## Wording
|Git|Explanation|
|:-------|:--------|
|Working Tree|Directory on your machine (aka lokal directory) that uses Git|
|||
|||
|||
|||
|||
|||
|||
|||

| Command                                 | Function                                                    |
|-----------------------------------------|-------------------------------------------------------------|
| git                                     | list all git commands                                       |
| q                                       | Quit git process                                            |
| git status                              | show all local changes                                      |
| git diff <file>                         | show differences of original and changed file               |
| git branch                              | list all local branches                                     |
| git branch -a                           | list all local and all remote repository                    |
| git clone <url>                         | load project from remote repository                         |
| git pull                                | download changes from remote repository to local repository |
| git push                                | upload local changes to remote repository                   |
| git checkout <branch>                   | switch to an existing branch                                |
| git checkout -b <branch>                | create new branch and switch to it                          |
| git add <file>                          | load changes in staging area                                |
| git add .                               | load all changes at once in staging area                    |
| git commit                              | open editor and write commit message                        |
| git commit -m "<Message>"               | commit with a short message                                 |
| git commit --allow-empty -m "<Message>" | git allows commit without any changes                       |
| git log                                 | show commit history                                         |
<hr>

## Get In
| Function                                                   | Command                                  |
|------------------------------------------------------------|:------------------------------------------:|
| List all Git commands:                                      | `git`                                      |
| Show help for a Git command:                                | `git help <command>`                       |

## Get Around on Your Machine
| Function                                                   | Command                                    |
|------------------------------------------------------------|:------------------------------------------:|
| Create a new Git working tree (so called 'initializing'):  | `git init <name-of-directory-to-create>`   |
| Initialize an existing directory as Git working tree:      | change into directory, then `git init`     |




 
| Function                                                   | Command                                  |
|------------------------------------------------------------|:------------------------------------------:|
| List all Git commands:                                      | `git`                                      |
| Show help for a Git command:                                | `git help <command>`                       |
| Show all changes in working tree (local project directory): | `git status`                               |
| Show all changes in working tree as short output:           | `git status -s`                               |
| show differences of original and changed file              | git diff <file>                          |
| list all local branches                                    | git branch                               |
| list all local and all remote repository                   | git branch -a                            |
| load project from remote repository                        | git clone <url>                          |
| download changes from remote repository to local repository| git pull                                 |
| upload local changes to remote repository                  | git push                                 |
| switch to an existing branch                               | git checkout <branch>                    |
| create new branch and switch to it                         | git checkout -b <branch>                 |
| load changes in staging area                               | git add <file>                           |
| load all changes at once in staging area                   | git add .                                |
| open editor and write commit message                       | git commit                               |
| commit with a short message                                | git commit -m "<Message>"                |
| git allows commit without any changes                      | git commit --allow-empty -m "<Message>"  |
| show commit history                                        | git log                                  |

| Quit git process                                           | q                                        |

