| Command                      | Description                                                                  |
| ---------------------------- | ---------------------------------------------------------------------------- |
| `git config`                 | Configure Git settings                                                       |
|                              | `git config <--flag> <key> <value>`                                          |
|                              | `git config --system`                                                        |
|                              | `git config --local`                                                         |
|                              | `git config --global`                                                        |
| -------------------          | ---------------------------------------------------------------------        |
| `git help`                   | Get help on Git commands or concepts                                         |
|                              | `git help <verb>`                                                            |
|                              | `git help config`                                                            |
|                              | `git add -h` (Quick refresher on available options for a command)            |
| -------------------          | ---------------------------------------------------------------------        |
| `git init`                   | Initialize a new Git repository                                              |
| `git clone`                  | Clone a repository into a new directory                                      |
|                              | `git clone <url> <sub-directory-name>`                                       |
| -------------------          | ---------------------------------------------------------------------        |
| `git status`                 | Get the status of files in the repository                                    |
| `git add`                    | Start tracking new files or stage changes for commit                         |
|                              | `git add <files/.>`                                                          |
| -------------------          | ---------------------------------------------------------------------        |
| `git status`                 | Check status of files (returns the status of newly added and modified files) |
| `git status -s`              | Check status of files in short format                                        |
| `gitignore`                  | Ignoring files in Git                                                        |
|                              | `<file-name>`                                                                |
|                              | `.gitignore`                                                                 |
| -------------------          | ---------------------------------------------------------------------        |
| `git diff`                   | Compares actual changes with what has been modified but is staged            |
| `git diff --staged`          | Shows the changes that have been staged and compares with previous snapshot  |
| `git commit`                 | Opens the default editor (vim) and asks to enter commit message              |
| `git commit -a -m "message"` | Skips the staging step and commits changes directly                          |
| `git rm <file-name>`         | Removes the file from the staging list                                       |

git log: list all commits from recent chronology
git log -2: two recent commits
git log --stat :abrevated changes in the file (during that commit)
git log --pretty=<oneline/short/full/fuller> :logs the more or less information about commits
git log --pretty = format:"%h %an" :logs the commit in desired format as %h means abbrivated hash and an means author name

git commit -amend: if you forget the to make changes, you write this command and editor opens you override the previous commit by replaceing with new one.

git reset HEAD <filename>: if the file is staged, it unstages that file and put into untracked list (hence modified list)
git checkout -- <filename>: Unmodify the modified file.

git restore --staged <filename>: Unstages the staged file (or git reset HEAD <filename>)
git restore <filename>: unmodify the modified files (git checkout -- <filename>)

git remote: lists the shortnames of each remote handle you’ve specified.
git remote -v: shows you the URLs that Git has stored for the shortname to be used when reading and writing to that remote
git remote add <shortname> <URL>: add remote with url represented with shortname

git fetch <shortname-remote>: downloads the changes from the remote to the local, remember not merges with your branch
git pull: downloads the changes from the remote to the local, and automatically merges the remote branch with your current branch

git remote show origin

git remote rename <old> <new-remote>
git remoite remove <remote-name>
