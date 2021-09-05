# All commands with "commit"

## Commit changes in the editor

This command will open a text editor in the terminal where you can write a full commit message. A commit message is made up of a short summary of changes, an empty line, and a full description of the changes after it.

`git commit`

## Commit changes with a message

You can add a commit message without opening the editor. This command lets you only specify a short summary for your commit message.

`git commit -m "[your commit message]"`

## Commit changes (and skip the staging area)

Combines the -a and -m options for creating a commit for all the staged changes and taking an inline commit message.

`git commit -a -m"[your commit message]"`

## Amend the most recent commit

Modifies the last commit. Staged changes are added to the previous commit.

`git commit --amend`
