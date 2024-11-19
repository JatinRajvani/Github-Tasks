# Part 2: Basic Workflow
## Task 3: Creating and Committing Files
### Create a file:
```
echo "Hello Git" > file1.txt
```
### Stage and commit the file:
```
git add file1.txt
git commit -m "Initial commit: Added file1.txt"
```

## Task 4: Viewing Changes
### Modify the file:
```
echo "Git is awesome!" >> file1.txt
```
### Check file status and differences:
The git diff command helps you see, compare, and understand changes in your project
```
git status
git diff
```

## Task 5: Undoing Changes
### Unstage a staged file:
The git reset command is used to undo the changes in your working directory and get back to a specific commit while discarding all the commits made after that one. 
```
git reset file1.txt
```
### Discard uncommitted changes:
```
git checkout -- file1.txt
```