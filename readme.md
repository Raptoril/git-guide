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
