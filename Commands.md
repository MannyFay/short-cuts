## Dev Tools
### Git
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
| eval "$(ssh-agent -s)"                  | use when ssh is a bitch                                     |
| ssh-add ~/.ssh/<my private key>         | add key to specific GitLab                                  |

### Docker
_____________
## Operating Systems


### Linux

#### Terminal
* Aliases
| Action | Function |
|-------|----------|
| alias commandName="command function"|Sets a shortcut for the command, saved in ~/.bashrc|

* Browse and search
| Action | Function |
|--------|-----------|
| ctrl r | search previous commands|
| repeat ctrl r after input | search through related commands |

* Bash Shortcuts
| Action | Function |
|------------|----------|
| ctrl a | move to beginning of current command |
| ctrl e | move to end of current command |
| ctrl arrow | jump through current command's words |
| alt B | move to previous word |
| alt + F | move to next word |
| tab | auto complete commands/filenames/etc |
| ctrl l | clear screen |

* History Tricks
| Action | Function |
|------------|-----------|
| !! | repeat previous command |
| history | previous commands, numbered |
| ! $commandNumber | executes command |
| sudo !! | execute previous command with sudo |

* Fix Typos
| Action | Function |
|-----------|---------|
| fc | correct previous command in editor |
| export EDITOR=$editorForFc | sets editor used by fc  in current bash session|
| save previous in ./bashrc | sets edior permanently |

* Screen Windows
| Action | Function |
|------------|------------|
|install screen | |



| Command                   | Function                             |
|---------------------------|--------------------------------------|
| ls /usr/bin/php*          | list installed php versions          |
| alias php=/usr/bin/php8.1 | Switch active php version            |
| dpkg -l &#124; grep php   | lists all installed php packages     |
| $(dpkg -l &#124; grep php &#123; awk '{print $2}') | This command uses dpkg -l to list all installed packages, pipes the output to grep to filter only the PHP packages, and then uses awk to extract the package names.  |
|


### MacOS
| Command | Function |
|---------|----------|
