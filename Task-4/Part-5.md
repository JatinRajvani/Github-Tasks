# Part 5: Tagging Commits (git tag)
## Task 9: Tag a Commit
### Tag the current commit with a version number:
Explanation:-Tags serve as clear markers for key points in the project's lifecycle, making it simpler to track and manage changes. Now, I use both commit hashes and tags to create a robust version control system.
```
git tag -a v1.0 -m "Initial release"
```
### List all tags:
```
git tag
```
## Task 10: Tag a Specific Commit
### Tag a specific commit by its hash:
```
git tag -a v1.1 <commit-hash> -m "Bug fix"
```
## Task 11: Push Tags to Remote
### Push a specific tag to the remote repository:
```
git push origin v1.0
```
### Push all tags to the remote repository:
```
git push --tags
```
