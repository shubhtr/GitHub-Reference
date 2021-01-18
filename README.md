# GitHub Reference

# Frequently Used

    $ git clone https://www.github.com/username/project1
    $ cd project1
    $ git config user.email "123456+username@users.noreply.github.com"
    $ git config user.name "John Smith"
    $ git push origin main

# Create new git

    $ git init
    $ git add --all
    $ git commit -m "Message"
    $ git remote add https://github.com/gitname.git

# Git local changes

    $ git status
    $ git add --all
    $ git add -p file

# Git history

    $ git log
    $ git log -p file
    $ git blame file

# Git branch

    $ git branch -av
    $ git branch new-branch-name
    $ git checkout branch

# Git undo

    $ git reset --hard HEAD
    $ git checkout HEAD file
    $ git revert commitID

# Other commands

## List local branches

    $ git branch

## Commit

    $ git commit -am 'Commit comment'

## Create a new branch

    # go to the base branch first
    $ git checkout -b new_branch_name

# switch to an existing branch

    $ git checkout branch_name

# push a local branch to a remote (GitHub)

    $ git push -u origin branch_name

# pull changes from a remote (GitHub)

# switch to a branch to merge the remote to the local

    $ git pull

