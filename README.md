
### Installation:
```
sudo yum install git
git --version
```

### Config
```
git config --global user.name "shamim"
git config --global user.email "tester@example.com"
```

### Initialization
```
git init

# create new local branch
git branch -m main

# show remote origin
git remote -v

# show all remote branch
git branch -r

# show remote and local branch
git branch --all

# change branch
git switch main
git checkout main
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
