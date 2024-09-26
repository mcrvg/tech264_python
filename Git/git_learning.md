# Git learning

**cd** -->open folders if there are space in the name folder we have to use "
**ls** -->list files 
**pwd** --> where are we right now?

# CORE COMMANDS 
git init: Initializes a new Git repository in the current directory.
git clone: Creates a local copy of a remote Git repository.
git add: Stages changes for inclusion in the next commit.
git commit: Creates a new commit with the staged changes.
git status: Shows the current status of the working directory and staging area.
git log: Displays the commit history of the repository.

# Steps GitHub
echo "# tech-264-git" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/mcrvg/tech-264-git.git
git push -u origin main

# Branching and Merging:
git branch: Creates, lists, or deletes branches.
git checkout: Switches to a different branch.
git merge: Merges changes from one branch into another.

# Remote Repositories:
git remote: Manages remote repositories associated with the local repository.
git push: Pushes commits to a remote repository.
git pull: Fetches changes from a remote repository and merges them into the current branch.   

# Other Useful Commands:
git diff: Shows the differences between files or commits.
git reset: Undoes changes or commits.
git revert: Reverses the effect of a specific commit.
git tag: Creates tags to mark specific points in the repository's history.


