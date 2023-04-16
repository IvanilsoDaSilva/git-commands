# GIT

## 1. Copy a remote repository
```
git clone {remote repository link}
```

## 2. Add changes from a local repository
```
git add {path of the file to be added or use "*" or also "." to add all changes}
```

## 3. Pack changes from a local repository into a commit
```
git commit -m {description}
```

## 4. Update local repository from remote repository
```
git push --set-upstream {remote repository link} {remote branch name}
```

## 5. Update local repository from remote repository
```
git fetch --prune --all
```

## 6. Show local repository branches
```
git branch
```

## 7. Show remoto repository branches
```
git branch -a
```

## 8. Switch between local branches
```
git checkout {branch name}
```

## 8. Create a local branch
```
git checkout -b {branch name}
```

## 9. Shows detailed information about a branch
```
git show
```

## 10. Show the commit history of a repository
```
git log
```

## 10. Show uncommitted changes from a branch
```
git status
```

## 11. Update local branch from remote
```
git pull origin
```

## 12. Delete a remote branch
```
git push origin :{branch name}
```

## 13. Delete a local branch
```
git branch -d :{branch name}
```

## 14. Delete a local branch(forced)
```
git branch -D :{branch name}
```

## 15. Undo changes to created files
```
git clean -f -d
```

## 15. Undo changes
```
git checkout .
```

