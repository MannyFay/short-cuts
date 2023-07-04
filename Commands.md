## Dev Tools
### Git
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
