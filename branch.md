# All commands with "branch"

## See all list branches

Show a list of all branches and mark the current branch with an asterisk and highlight it in green.

`git branch`

## See List branch

List all the remote branches.

`git branch -a`

## Create a new branch

Create new branch under a specified name.

`git branch branch_name`

## Delete a branch

Deletes a branch. If there are unmerged changes, Git does not allow you to delete it.

`git branch -d branch_name`

## Force delete a branch

Forces delete the branch, even if there are unmerged changes. Execute this command when you are sure to delete it permanently.

`git branch -D branch_name`

## Move or rename a branch

Moves or renames the current branch to branch_name.

`git branch -m branch_name`

## Check remote branches

This command shows the name of all remote branches that Git is tracking for the current repository.

`git branch -r`
