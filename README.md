# Git Lab 1

## Project Description
This project is for practicing Git and GitHub commands.

## Steps With Commands

### 1. Create SSH Key
```
ssh-keygen -t ed25519 -C "ma6849312@gmail.com"
cat ~/.ssh/id_ed25519.pub
```

### 2. Configure Git
```

git config --global user.name "Mariam Ali"
git config --global user.email "ma6849312@gmail.com"
```

### 3. Create Local Repository
```
git init
```

### 4. Create Files
```

touch README.md
```

Python file:
```

print("Mariam Ali")
```
### 5. Add and Commit
```

git add .
git commit -m "first commit"
```
### 6. Connect to GitHub
```
git remote add origin git@github.com:MariamAli581/git-lab1.git
```

### 7. Push to GitHub
```
git branch -M main
git push -u origin main
```

### 8. Delete Last Commits
```
git reset --hard HEAD~2
```
### 9. Add New Commit After Deletion
```
git add .
git commit -m "commit after deletion"
```

### 10. Amend Last Commit

Add to file:
```

print("lab Done")
```

### Then:
```
git add .
git commit --amend -m "finish"
```
### ---------------
### Revert Operation
```
git revert HEAD
git push -f origin main

```
