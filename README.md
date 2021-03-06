# git-templates
Template for Cloudrexx-related GIT repositories

## What's this
This contains all GIT hooks we use to develop for Cloudrexx. Currently this includes:
- PHP Linter
- Commit message linter

This list will probably get longer over time.

## Prerequisites
Obviously, this needs GIT to be installed. In addition here's a list of
requirements by the linters:
- PHP Linter: Either PHP or Docker is required, otherwise this linter is disabled
- Commit message linter: Requires Docker

## Installation
`git clone https://github.com/Cloudrexx/git-templates.git ~/.git_template`

After cloning the repository you should set your git templatedir:
`git config --global init.templatedir '~/.git_template'` 
## Update
To update to the newest version of our templates simply execute `git pull` in `~/.git_template`.

To update existing repositories call `git init` from within the repository. Don't worry, this simply replaces the files from the template in your ".git" folder.
