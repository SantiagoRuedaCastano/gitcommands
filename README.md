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
