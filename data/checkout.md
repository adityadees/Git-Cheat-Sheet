# All commands with "checkout"

## Switch to a newly created branch

Use a different or a newly created branch.

`git checkout [branch_name]`

## How to create a branch in Git and switch to it immediately

In a single command, you can create and switch to a new branch right away.

`git checkout -b [branch_name]`

## Create and switch based on existing branch

The git checkout -b bases the new_branch off the current HEAD. In the given example, `existing_branch` will base new_branch off instead of the current HEAD.

`git checkout -b [new_branch] [existing_branch]`
