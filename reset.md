# All commands with "reset"

## Unstage a file

Unstage a file without overwriting changes.

`git reset [file]`

## Undo change to specified commit

Undo any changes introduced after the specified commit.

`git reset [commit]`

## Renaming branches

This pushes the `LOCALBRANCHNAME` to your `REMOTENAME`, but it is renamed to `REMOTEBRANCHNAME`.

`git push  [REMOTENAME] [LOCALBRANCHNAME]:[REMOTEBRANCHNAME]`

## Force Upload

Forces the push even if it results in a non-fast-forward merge. Be sure that nobody has pulled the commits before using the --force option.

`git push [remote] --force`

## Upload all

Pushes all of the local branches to the remote repository.

`git push [remote] --all`

## Upload single tags

Pushes the spesific tags from the local branches to the remote repository.

`git push  [REMOTENAME] [TAGNAME]`

## Upload all tags

Pushes all tags from the local branches to the remote repository.

`git push [remote] --tags`

## Deleting a remote branch or tag

Note that there is a space before the colon. The command resembles the same steps you'd take to rename a branch. However, here, you're telling Git to push nothing into BRANCHNAME on REMOTENAME. Because of this, git push deletes the branch on the remote repository.

`git push  [REMOTENAME] :[BRANCHNAME]`
