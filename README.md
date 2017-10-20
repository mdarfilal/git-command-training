# Git command line training

## Create branch and switch
git checkout -b develop

## Push the branch
git push origin develop

## Rebase commit in develop to resolve conflicts in your branch
git rebase develop

## Return to develop and merge changes
git checkout develop
git merge us-init

# Delete local branch
git branch -d us-init

# Delete remote branch
git push origin :us-init