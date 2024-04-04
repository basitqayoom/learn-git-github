# Git Commands Cheat Sheet

| Command                                | Description                                                                 |
| -------------------------------------- | --------------------------------------------------------------------------- |
| `git config`                           | Configure Git settings                                                      |
|                                        | `git config <--flag> <key> <value>`                                         |
|                                        | `git config --system`                                                       |
|                                        | `git config --local`                                                        |
|                                        | `git config --global`                                                       |
| `git help`                             | Get help on Git commands or concepts                                        |
|                                        | `git help <verb>`                                                           |
|                                        | `git help config`                                                           |
|                                        | `git add -h` (Quick refresher on available options for a command)           |
| `git init`                             | Initialize a new Git repository                                             |
| `git clone`                            | Clone a repository into a new directory                                     |
|                                        | `git clone <url> <sub-directory-name>`                                      |
| `git status`                           | Get the status of files in the repository                                   |
| `git add`                              | Start tracking new files or stage changes for commit                        |
|                                        | `git add <files/.>`                                                         |
| `git diff`                             | Compares actual changes with what has been modified but is staged           |
| `git diff --staged`                    | Shows the changes that have been staged and compares with previous snapshot |
| `git commit`                           | Opens the default editor (vim) and asks to enter commit message             |
| `git commit -a -m "message"`           | Skips the staging step and commits changes directly                         |
| `git rm <file-name>`                   | Removes the file from the staging list                                      |
| `git log`                              | Lists all commits from recent chronology                                    |
| `git log -2`                           | Lists two recent commits                                                    |
| `git log --stat`                       | Abbreviated changes in the file during that commit                          |
| `git log --pretty=<format>`            | Logs commits in desired format                                              |
| `git commit --amend`                   | Overrides the previous commit by replacing it with a new one                |
| `git reset HEAD <filename>`            | Unstages the staged file and puts it into the untracked list                |
| `git checkout -- <filename>`           | Unmodifies the modified file                                                |
| `git restore --staged <filename>`      | Unstages the staged file                                                    |
| `git restore <filename>`               | Unmodifies the modified files                                               |
| `git remote`                           | Lists the shortnames of each remote handle you've specified                 |
|                                        | `git remote`                                                                |
| `git remote -v`                        | Shows the URLs that Git has stored for the shortname                        |
|                                        | `git remote -v`                                                             |
| `git remote add <shortname> <URL>`     | Adds a remote with the specified URL and shortname                          |
|                                        | `git remote add <shortname> <URL>`                                          |
| `git fetch <shortname-remote>`         | Downloads changes from the remote to the local, does not merge              |
|                                        | `git fetch <shortname-remote>`                                              |
| `git pull`                             | Downloads changes from the remote to the local and merges                   |
|                                        | `git pull`                                                                  |
| `git remote show origin`               | Shows information about the remote named 'origin'                           |
|                                        | `git remote show origin`                                                    |
| `git remote rename <old> <new-remote>` | Renames a remote                                                            |
|                                        | `git remote rename <old> <new-remote>`                                      |
| `git remote remove <remote-name>`      | Removes the specified remote                                                |
|                                        | `git remote remove <remote-name>`                                           |
