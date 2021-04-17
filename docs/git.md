# Basic git usage

# Creating a new repository in existing current directory

git init *creates new .git repository in current directory*

## Staging files for next commit

git add **filename**  *stages **filename** for next commit*
git add .             *stages all files*
git add -A            *stages all files in repository tree*
git add -u            *stages new and modified files but not deleted ones*

## committing staged files

git commit -m **commit message**


Creating a github repository for a new project
Creating a github repository for a project oa;ready on local machine
Restoring an old version of a file

git status *shows which branch is current and what staged and unstaged changes exist*

git log --oneline *shows history of commits in repository*

git checkout **commit-id** **filename** *restores an old version of a ile from the repository*

# Github connection

## Cloning an existing Github repository into empty local directory 

git clone **url**