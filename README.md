# LearnHere
A repository to test out git commands

### Clone this repo
To start working with this repository:
```
git clone https://github.com/RicoCruz6/LearnHere.git
cd LearnMore
```

### Creating a new local branch
Get latest from remote repo:
```
git checkout master
git pull
```

To create a new local branch: `git checkout -b <branch name>`

Note: Try and branch from the master branch, this will create your new branch from the master branch.

Example: `git checkout -b example_branch`

Optional add tracking to newly created branch: `git push -u origin <branch name>`

Example:`git push -u origin example-branch`

### Commiting changes to local
Once you are in a logical place to stop, or have completed your task/story you need to commit your changes.

Optional steps:

* Use git status to check what files have changed
  * `git status`
 * Use git diff to review specific changes
  * `git diff`
* Get latest from the repo
 * `git pull`
* Merge in master branch
 * `git merge master`

If you are commiting all your changes: `git commit -am <commit message>`

Example: `git commit -am "I am commiting all my changes"`

If you only want to commit certain files:
1. Add the files you want to commit
  * `git add <path_to_file/file>`
2. Commit the files
  * `git commit -m <commit message>`
  
### Pushing your branch to remote repo
Optional steps:

* Check status to make sure you are on correct branch and did not forget any files
  * `git status`
* Check that all the commits you mean to push up are there
  * `git log -<n>` n being the number of commits you want to display
  
To push your branch to the remote repo: `git push <remote> HEAD`

Example: `git push origin HEAD`
  
  
