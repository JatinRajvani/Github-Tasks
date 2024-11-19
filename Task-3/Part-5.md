# Part-5
## Task 8: Make Changes in a Branch

### 1. Add new file in the new branch
```
    echo "New file" >> new_file.txt
```
### 2. Add to stagging area and commit 
```
    git add new_file
    git commit -m "File added"
```

#### Task 9: Merging Branches

### 1. To merge branch first we switch into main branch
```
    git checkout main
```
### 2. Merge the new branch into main
```
    git merge new_branch
```
