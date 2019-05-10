# Git CLI Cheat-Sheet

## Gettings started
You will either create a new repository for scratch with `init` or `clone` an existing repository
#### Initialise a new repository in the current directory 

`git init`

#### Link to remote repository
`git remote add origin <url-of-existing-remote-repo>`

'origin' is just the name of the remote. You can name it anything. 'origin' is just the default everyone goes with. If you need a second remote, then you can give it another name.

#### Clone an exising respository
`git clone <url-of-existing-repo>`


## Staging files
Before you commit files you need to stage them first. This way you can pick and choose which files to commit and which to leave out of a commit.
#### Stage an individual file
`git add <filename>`
#### Stage all altered files
`git add .`    

#### Unstaging files
`git rm <filename>`

## Commit
This will commit the staged files only.

#### Commit with message
`git commit -m <commit-message>`

## Checkout
#### Checkout existing branch
`git checkout <exising-branch-name>`

#### Create and checkout new branch
`git checkout -b <new-branch-name>`

#### Discard all changes
`git checkout .`

## Remote Commands

#### Fetch
`git fetch`

Fetches branches and tags

#### Pull
`git pull`

#### Push
`git push`







