# All commands with "log"

## See commit history

Shows the commit history for the current repository.

`git log`

## See commit history including changes

Shows the commit's history including all files and their changes.

`git log -p`

## See log stats

Show some statistics about the changes in each commit, including line(s) changed and file names.

`git log --stat`

## See log commit include moved path

show all commit logs with indication of any paths that moved.

`git log --stat -M`

## See log commit in single line

Fits each commit on a single line which is useful for an overview of the project history.

`git log --graph --oneline --all`

## Check the current commits log of a remote repo in Git

Find out the remote repository log commit.

`git log origin/main`
