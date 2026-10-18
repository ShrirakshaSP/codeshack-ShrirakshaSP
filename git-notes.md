Git Command Notes
1. git init
Initializes a new Git repository.

Example:
git init

2. git clone
Creates a local copy of a remote repository.

Example:
git clone https://github.com/USERNAME/PROJECT.git

3. git status
Shows the current branch and the status of changed files.

Example:
git status

4. git add
Stages changes for the next commit.

Example:
git add README.md

5. git commit
Saves staged changes as a checkpoint.

Example:
git commit -m "Add project documentation"

6. git log
Displays the commit history.

Example:
git log --oneline

7. git diff
Shows unstaged changes to tracked files.

Example:
git diff

To view staged changes:
git diff --staged

8. git push
Uploads local commits to GitHub.

Example:
git push

9. git pull
Downloads and integrates remote changes.

Example:
git pull origin master

10. git fetch
Downloads remote updates without integrating them into your current branch.

Example:
git fetch origin

Additional Useful Commands
git branch
Lists local branches.

Example:
git branch

git switch -c
Creates and switches to a new branch.

Example:
git switch -c feature/documentation

git remote -v
Displays remote repository URLs.

Example:
git remote -v

git show
Displays details about a commit.

Example:
git show HEAD

Difference Between Fetch and Pull
git fetch downloads updates but does not integrate them.
git pull downloads and integrates updates.
git add stages changes.
git commit saves changes locally.
git push uploads commits to GitHub.

Example Daily Git Workflow
Check the working tree:
git status
Review your changes:
git diff
Stage a file:
git add README.md
Save your changes:
git commit -m "Update handbook introduction"
Upload commits to GitHub:
git push
View the commit history:
git log --oneline
Why Git Is Useful
Git helps developers track project history, work on separate features, review changes, and collaborate without losing previous versions of their work.