# VITMAS_TASK_20MID0185
git config
Helps to set configuration options for your Git installation

git init
To start a new repository

git clone
To obtain a repository from an existing URL.

git add
To add a file to staging area

git commit
To record or snapshot the file permanently in the version history.

git commit --amend
To amend the most recent commit.

git diff
Shows the file differences which are not yet staged.

git diff –staged
Shows the differences between the files in the staging area and the latest version present.

git diff [first branch] [second branch]

Shows the differences between the two branches mentioned.

git reset [file]
Unstages the file, but it preserves the file contents.

git reset [commit]
Undoes all the commits after the specified commit and preserves the changes locally.

git reset –hard [commit]
Discards all history and goes back to the specified commit.

git status
To list all the files that have to be committed.

git rm
To delete the file from your working directory and stages the deletion.

git log
To list the version history for the current branch.

git log –follow[file]
To list the version history for a file, including the renaming of files also.

git show
To show the metadata and content changes of the specified commit.

git tag
To give tags to the specified commit.

git branch
Lists all the local branches in the current repository.

git branch [branch name]
Creats a new branch name

git branch -d [branch name]
Delets the branch

git checkout
To switch from one branch to another.

git merge
Merges the specified branch’s history into the current branch.

git remote
To connect your local repository to the remote server.

git push [variable name] master
Sends the committed changes of master branch to your remote repository.

git push [variable name] [branch]
Sends the branch commits to your remote repository.

git push –all [variable name]
Pushes all branches to your remote repository.

git push [variable name] :[branch name]
Deletes a branch on your remote repository.

git pull
Fetches and merges changes on the remote server to your working directory.

git stash save
This command temporarily stores all the modified tracked files.

git stash pop
This command restores the most recently stashed files.

git stash list
This command lists all stashed changesets.

git stash drop
This command discards the most recently stashed changeset.
