# git-tutorial

Start Fresh: Make sure your main branch is up-to-date with the remote repository.

```
git checkout main
git pull origin main
```
Create a New Branch: Create a new feature branch.

```
git checkout -b feature-day1
```

Work and Commit: Add the new feature and commit changes.

```
git add .
git commit -m "Added feature for Day 1"
```
Push the Feature Branch: Once satisfied, push the feature branch to the remote repository.
```
git push -u origin feature-day1
```
Code Review and Merge: Create a Pull Request (PR) and after review, merge into main.
