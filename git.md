# Git stuff

## How to rename a git branch

Renaming a git branch is easy. Really easy. No rocket sience. Even this line is longer than the actual command. So, please, for the love of God: Remember this!!  

```git branch -m old_name new_name```

Delete the old-name remote branch and push the new-name local branch

```git push origin :old_name new_name```

Reset the upstream branch

```git push origin -u new_name```