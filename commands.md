
# Git Commands Cheat Sheet

### Setup and Configuration

**Configure Username and Email**
```
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

**Check Git Configuration**
```
git config --list
```

### Creating a Repository

**Initialize a new Git repository**
```
git init
```

**Clone an existing repository**
```
git clone <repository_url>
```

### Basic Commands

**Check the status of the repository**
```
git status
```

**Add files to the staging area**
```
git add <file>
git add . # Add all files
```

**Commit changes**
```
git commit -m "Commit message"
```

**View commit history**
```
git log
```

### Branching and Merging

**Create a new branch**
```
git branch <branch_name>
```

**Switch to another branch**
```
git checkout <branch_name>
```

**Create and switch to a new branch**
```
git checkout -b <branch_name>
```

**Merge branches**
```
git merge <branch_name>
```

**Delete a branch**
```
git branch -d <branch_name>
```

### Remote Repositories

**Add a remote repository**
```
git remote add origin <repository_url>
```

**Push changes to a remote repository**
```
git push origin <branch_name>
```

**Pull changes from a remote repository**
```
git pull origin <branch_name>
```

**List all remote repositories**
```
git remote -v
```

### Stashing

**Stash changes**
```
git stash
```

**Apply stashed changes**
```
git stash apply
```

**List stashes**
```
git stash list
```

### Undoing Changes

**Undo local changes (before commit)**
```
git checkout -- <file>
```

**Unstage files from the staging area**
```
git reset <file>
```

**Revert a commit**
```
git revert <commit_hash>
```

**Reset to a previous commit (dangerous!)**
```
git reset --hard <commit_hash>
```

### Tags

**Create a tag**
```
git tag <tag_name>
```

**Push tags to a remote repository**
```
git push origin --tags
```

### Viewing and Comparing

**Show changes between commits or branches**
```
git diff <commit1> <commit2>
```

**Show file content at a specific commit**
```
git show <commit_hash>:<file_path>
```

### Git Help

**Get help for any Git command**
```
git help <command>
```

