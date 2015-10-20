## Cheat Sheet

Whenever you're confused about git, come read this cheat sheet. Remember that all git commands can be run with the `--help` option. For example:

`$ git branch --help` or `$git log --help`

### Essential Git Commands

####Create a new git repository
`$ git init` - Create a new, local repository

#### Repo Status
`$ git status` - Check the status of your current repository and see which files have changed.

`$ git diff` - __Fill Me Out__

#### Repo History
`$ git log` - __Fill Me Out__

`$ git log --oneline --decorate --color --graph --all` - __Fill Me Out__

`$ git log -p [filename]` __Fill Me Out__

#### Stage files to commit
`$ git add <filename>` - Add file contents to the index

`$ git add -A` - Update the index not only where the working tree has a file matching. If no <pathspec> is given when -A option is used, all files in the entire working tree

#### Commit changes in staged files
`$ git commit -m "<commit message>"` - Commits the staged snapshot with a message.

#### Branching
`$ git branch <branch name>` - Creates a new branch within the current repository, using the given name.

`$ git branch` - Displays all existing branches in the current repository.

`$ git checkout <branch name>` - Allows the user to switch between branches in the current repository.

#### Merging

`$ git merge <branch name>` - Allows the user to merge changes between different branches.
