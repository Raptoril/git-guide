# git guide

### 1. Config user
```
git config --global user.name "Your full name"
git config --global user.email "Your-email-address"
git config --list
```

### 2. Init git
```
mkdir "repository Name"
cd ".\Repository Name"
git Init
dir -hidden
```

### 3. First commit
```
git status
git add .\file.ext
git status
git commit -m  "commit message: brief description"
git status
```

### 4. Create branch
```
git branch dir/branch-name
git branch
```

### 5. Check out branch
```
git checout dir/branch-name
git status
```

### 6. Merge to master
```
git checkout master
git status
git merger dir/branch name
git status
git log
```

### 7. Create stash
```
git status
git stash
git status
```

### 8. Apply stash
```
git stash list
git stash Apply
git status
```

### 9. Delete stash 
```

git stash list
git stash drop 1
git stash list
```
### 10. Pop stash
```
git stash list
git stash Popgit stash  list
```
### 11. Revert Commit
```
git log --oneline
git revert [Commit_ID]
```
### 12. Revert Commit
```
git log --oneline
git cherry-pick [Commit_ID]
```
### 13. Reset
```
git stash list
git stash Popgit stash  list
tambien puedes usar los 3 resets que vienen por defecto en el sublime merge que son:
git Reset --soft
git reset 
git reset --hard
otros resets son
git reset "nombre del archivo"
git reset <# del commit>
```
### 14.create patch
```
git stash list
git stash Popgit stash  list
tambien puees usar:
git diff > cambios.patch
git diff --chached > cambios.patch
git format-patch -1 <commit-hash>
```
### 15. Apply patch
```
git stash list
git stash Popgit stash  list
```
### 16. Init GitHub
```
Git remote add origin [REMOTE-URL]
git push -u origin master
git push origin --all
```
