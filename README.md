
### Installation:
```
sudo yum install git
git --version
```

### Config
```
git config --global user.name "shamim"
git config --global user.email "test@example.com"
```

### Initialization
```
git init
git branch -m main
git remote -v
```

### Add and Commit
```
# add a specific file
git add <file-name>

# add all files
git add .

# check status 
git status

# commit
git commit -m "initial comment"

# push into remote git repo
git push -u origin main
```
### Diff
```
# shows differences between working area and starging area
git diff
# shows differencew between starging area and local repository
git diff --staged
```

### TEST
