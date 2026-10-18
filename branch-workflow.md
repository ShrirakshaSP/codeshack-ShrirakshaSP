Branch Workflow Guide
What Is a Branch?
A branch is a separate line of development that lets developers work on changes independently.

Create a Branch
git switch -c feature/documentation

This creates a new branch and switches to it.

Check Your Branch
git branch

The asterisk indicates the current branch.

Push a Branch
git push -u origin feature/documentation

This uploads the branch to GitHub and sets its upstream.

Team Collaboration Rules
Each member should work on their own branch.
Do not commit directly to main.
Use meaningful commit messages.
Push your branch to GitHub.
Open a pull request for review before merging.
Example Workflow
Update your local repository.
Create a feature branch.
Make your changes.
Review changes using git diff.
Stage changes using git add.
Commit using git commit.
Push using git push.
Open a pull request on GitHub.

## Benefits of Feature Branches

- Developers can work independently.
- Changes can be reviewed before merging.
- The main branch remains protected from unfinished work.
- Multiple features can be developed simultaneously.
