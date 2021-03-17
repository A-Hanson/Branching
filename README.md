## Git Branching Cheat Sheet

### Basic git Commands
* `git init` - initialize working directory with git repository
* `git status` - show status of working directory / repository
* `git add .` - stage all new changes for commit
* `git commit -m "message"` - commit staged changes to local repository
* `git log` - displays prior commits
* `git log --oneline` - displays prior commits on one line each
* `git log` - displays prior commits
* `git config --list` - list current git configuration
* `git config --help` - list options and syntax for git config

### Branching Commands
* `git branch -M newName` - Rename current branch to `newName`
* `git branch newBranch` - Create branch `newBranch`
* `git branch` - list local branches, indicating current branch
* `git checkout newBranch` - Make `newBranch` the current branch
* `git checkout -b otherBranch` - Create and checkout `otherBranch`
