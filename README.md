# All-git-basic-commands
## Basic Git Commands for all.
#### Initialize a new git Repository
`git init`
#### Clone a git repository
`git clone <repository_URL>`
#### Check status of your repositoy
`git status`
#### Stage changes for commit
`git add <FileName>`
#### Commit staged changes 
`git commit -m "Your Commit Message will be here"`
#### Commit all changes including untracked files
`git commit -am "Your Commit Message will be here"`
#### View Commit history
`git log`
#### Create a new branch
`git branch <branch_name>`
#### Switch to a different branch
`git checkout <branch_name>`
#### Create and switch to a new branch
`git checkout -b <branch_name>`
#### Pull changes from a remote repository
`git pull origin <branch_name>`
#### Push changes to remote repository
`git push origin <branch_name>`
#### Remove a file from version control but keep it locally 
`git rm --cached <file_name>`
#### Discrad local changes and revert to the last commit
`git reset --hard HEAD`
#### Tag a specific commit
`git tag <tag_name> <commit_hash>`
#### View All tags
`git tag`
#### Rebase changes from one repositiry to another
`git rebase <branch_name> <feature_name>`
#### Amend the last commit
`git commit amend  -m "New Commit Message"`
#### View the difference between commits
`git differ <commit1> <commit2>`
#### Configure Global user name and password
`git config --global user.name "Your user name"`
`git config --global user.email "your@email.com"`
#### View Your git configuration
`git config --list`
#### Discard changes in a specific file
`git checkout --<filename>`
#### Create a stash of changes for later use
`git stash save "Your stash message here"`
#### Apply stash to changes
`git stash apply`
#### Remove a stash of changes
`git stash drop`
#### List all stashes
`git stash list`
#### Show information about a specific commit
`git show <comit_hash>`
#### Remove a branch 
`git branch -d <branch_name>`
#### Remove a branch forcefully
`git branch -D <branch_name>`
#### Undo the last commit but keep changes
`git reset HEAD~`
#### Undo the last commit and discard changes
`git reset --hard HEAD~`
#### Fetch changes from remote repository
`git fetch origin`
#### Squash multiple commits into one
`git rebase -i HEAD~<number_of_commits>`
#### View Remote Repositories
`git remote -v`
#### Add a remote repository
`git remote add <remote_name> <repository_url>`
#### Rename a branch
`git branch -m <old_branch_name> <new_branch_name>`
#### Change remote URL of repository
`git remote set-url origin <new_repository_url>`
#### View changes in specifice commit
`git show <commit_hash>`
#### Manage a remote branch in your local branch
`git pull origin <remote_branch>:<local_branch>`
#### Rename a file while keeping version history
`git mv <old_file_name> <new_file_name>`
#### Reset the changes in a specific file
`git checkout HEAD <file_name>`
#### Remove a remote repository
`git remote remove <remote_name>`
#### Show changes between the working directory and the index
`git diff`


