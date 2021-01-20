## Everyday Git Cheat Sheet

#### Add - Stages Files
`git add .` - select all

`git add . -p` - select specific chunks

`git add src` - directory only

#### Check what is staged & not staged
`git status`

#### Commit
`git commit -m "<Verb> <Noun>"` - Recommend explicit commit messages, such as

`git commit -m "Add unit test for myFunction()"`

#### Push
`git push` - commits branch to remote

`git push --set-upstream origin <branch>` - create upstream reference and commits branch to remote

#### Create new branch
`git checkout -b <new-branch>`

#### Stash
`git stash` - creates a stash of current staged files

`git stash list` - shows what's stashed

`git stash pop` - Apply stashed, last in first out

