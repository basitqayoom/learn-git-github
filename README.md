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
