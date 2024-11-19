# Part 2: Rewriting History with git rebase
## Task 4: Rebase Commits to a New Base
Rebase the current branch onto main:
```
git rebase main
```
Explanation: This command applies the commits from your current branch on top of the latest commit from main.
## Resolve any conflicts that may arise during rebase, and continue:
```
git rebase --continue
```
## Task 5: Canceling a Rebase
### If a rebase goes wrong, abort it:
```
git rebase --abort
```