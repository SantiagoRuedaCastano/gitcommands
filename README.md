# git commands


## Create branches 

    git branch newfeature

    git checkout newfeature


    git push remote-repo newfeature

## Delete branches
    git branch -d newfeature


    git push origin --delete newfeature


## Clean branch
    git reset --hard HEAD

    git clean -xfd

    git pull

## Delete a commit from a branch

    git reset --hard <hash-commit-id>

    git push origin HEAD --force
    
    
## Reset a file as another branch

    git checkout <branch> -- <path/to/file>

## Reset git

    git config --local --unset credential.helper
    git config --global --unset credential.helper
    git config --system --unset credential.helper
    
    git config --local --unset user.name
    git config --global --unset user.name
    git config --system --unset user.name
    
    git config --local --unset user.email
    git config --global --unset user.email
    git config --system --unset user.email

    
