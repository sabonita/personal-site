##  Notes on Git

#### `git status`
 
- use anytime
- shows changes that are staged or unstaged for commit

#### `git pull <repository> main`

- pulls a copy of the main branch from the specified GitHub repository
- generally `<respository>` is specified as `origin`

#### `git checkout -b <branch name>`

- creates and checks out a new branch specified by `<branch name>`
- drop `-b` when checking out an existing branch

#### `git add <file name>`

- stages changes made in file for commit
- `git add .` instead of a file name will stage all changes in current directory

#### `git commit -m "<message>"`

- commits staged changes with a commit message
- in which the `<message>` briefly explains the changes being committed 

#### `git push <repository> <branch>`

- pushes committed changes to the specified `<branch>` to GitHub in order to start pull request process
- generally `<repository>` is specified as `origin`