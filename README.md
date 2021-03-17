## GIT Branching Cheat Sheet

### Basic GIT Commands
* `git init` - initialize working directory with git repo
* `git status` - show status of working directory/repo
* `git add` - stage changes for commit
* `git commit -m ""` - commit staged changes to local repo
* `git log` - list commits
* `git log --oneline` - list commits in compact form
* `git config --list` - list current GIT config

### Branching Commands
* `git branch -M newName` - rename current branch
* `git branch newBranch` - create branch `newBranch`
* `git branch` - list local branches, indicating current branch
* `git checkout newBranch` - make `newBranch` the current branch
* `git checkout -b otherBranch` - create and checkout `otherBranch`
