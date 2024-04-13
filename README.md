# Git-Commands
- **Git init:** It create a empty repo in a specified directoty.
**command:**
`git init`
- **git clone :** we can clone the repo located on local machine
**command:**
`git clone <repo url >`
- **git config:** It set the configuartion option for git like(name,mail). 
**command:**
> git config --global user.name "name"
> git config --global user.mail "mail"
- **Git add:** It is used to stage the changes to next commit in Git. when we modified the files in git repositary git recognized those changes are unstaged.
**command:**
`git add <file>`
- **git commit -m :** It is used to save the staged changes to the local repositary. It creates a snapshot of the changes that we have staged using git add command.
**command:**
`git commit -m "message"`
- **git status:** It list the which files are staged and unstaged and untracked 
**command:**
`git status`
- **Git log:** It display the history of the git repositary. 
**Command:**
`git log`
- **git diff:** It is used to show the difference between the various states of git repositary.
**command:**
`git diff`
`git diff head`
`git diff --staged`
- **git commit -amend:** It is used to modify the most recent commit in git history.
**command:**
`git commit -amend`
- **git rebase <base>:** It is used to re apply the series of commits onto a different base commit. It integrate the changes from one branch to another branch
**command:**
`git rebase <base>`
- **git reflog:** It display the log of all actions taken your repositary including commits,checkouts,mergesrebase....
- **git branch:** It is used to list,delete and create the branch in git repositary.
**Commands:**
`git branch`
`git branch <branch name >`
`git branch feature`
git checkout -b <branch name>:














