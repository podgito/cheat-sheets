## Merging
#### I've finished with my branch <feature123> and want to push it and create a pull request
Make sure you've committed all your changes

`git add .`

`git commit -m "added new feature (A.K.A. loads of bugs)"`

Next as a best practice, merge master into your branch to take in changes made by other team members. (See rebase later)

`git fetch`

`git merge origin master`

Next push your branch

`git push`

If that command give you an error about remote tracking then run the following command. This will setup remote tracking for that branch.

`git push -u origin <branch-name>`

Create a pull request up on the server.