# All commands with "config"

## Check git configuration

To see a list of information about git configuration including user name and email.

`git config -l`

## Setup git username

Attach an author name to all commits that will appear in the version history.

`git config --global user.name "[yourUserName]"`

## Setup git email

Attach an email address to all commits by the current user.

`git config --global user.email "[yourEmail]"`

## Cache login credentials

Store login credentials in the cache so you don't have to type them in each time.

`git config --global credential.helper cache`

## Set automatic command line coloring for Git

Apply Git’s automatic command line coloring which helps you keep track and revise repository changes.

`git config --global color.ui auto`

## Ignore all file for all local repositories

System wide ignore patern for all local repositories. This setting lets you write a kind of global .gitignore file.

`git config --global core.excludesfile [file]`

## Create shortcut alias

Setting shortcuts for commonly used commands can speed up and simplify development.

`git config --global alias.[alias_name] [git_command]`
