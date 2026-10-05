Here is a **short README section** for Task 1:

# Task 1 — Git & GitHub Workflow

## Git Concepts

Branch:A separate line of development used to make changes without directly affecting `main`.
Commit:A saved snapshot of changes in the Git repository.
Remote:A reference to a repository hosted elsewhere, such as GitHub.
Pull Request:A request to merge changes from one branch into another, usually after review.

## Deleting vs Stopping Git Tracking

Deleting a file:Removes the file from the local computer and Git.
Stopping Git tracking:Removes the file from Git's tracking but keeps the file locally.

To stop tracking a file:

```bash
git rm --cached config.py
```

Then add it to `.gitignore` to prevent Git from tracking it again.

git commands:
git status
git add .
git checkout -b file
git rm --cached file

