# git_practising

## Undo local commits
### Keep changes
``` git reset HEAD~4 ``` 
for 4 commits
### Discard changes
``` git reset --hard HEAD~4 ``` for 4 commits

### Remove the file from git and add to .gitignore
```
git reset <fileName>
echo <fileName> >> .gitignore
```
