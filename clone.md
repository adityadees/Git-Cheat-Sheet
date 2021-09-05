# All commands with "clone"

## Clone a repository (local or remote via HTTP/SSH)

Target an existing repository and clone or copy it in a new directory.

`git clone [myRepoUrl]`

## Cloning to a certain folder

You should make a clone of the repository at `myRepoUrl` into the folder called `myFolder` on the local machine.

`git clone [myRepoUrl] [myFolder]`

## Cloning a certain tag

Clone the repository at [myRepoUrl] and clone only the ref for [myTag].

`git clone --branch [myTag] [myRepoUrl]`

## git clone branch

The `-branch` argument specifies a branch which should be cloned instead of the one the remote HEAD is indicating to, usually the master branch. Besides, you can pass a tag instead of a branch for the same effect.

`git clone -branch [myBranch] [myRepoUrl]`
