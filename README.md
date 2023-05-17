#Git Cheat Sheet

Overview of Git commands, and branching and merging.

##Basic Commands
* 'git init' - initialize local repository
* 'git add .' - add (stage) current working folder contents to local repo index
* 'git commit -m "Message"' - commit staged work to to local repo, with commit message

##Info Commands
* 'git status' - show commit status of local working folder
* 'git log' - list commit history of local working folder
* 'git log --oneline' - list commit history (compact format)
* 'git config -l' - list local Git configuration settings

##Branch Commands
* 'git branch' - list local branches
* 'git branch -m newName' - rename current local branch
* 'git branch branchName' -  create local branch 'branchName'
* 'git checkout branchName - move to local branch 'branchName'

## Remote Commands
* `git remote add remName remote` - connect local repo to remote repository `remoteUrl` with shortcut `remName` for the remote URL
* `git push remName BranchName` - push local commits to remote branch
