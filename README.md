# GIT Commands

### create git 
``` git init ```

### add remote url
``` git remote add <url> ```

### creating branch
``` git branch <branchName> ```

### move to branch
``` git checkout <branchName> ```

### create branch and move same time
``` git checkout -b <branchName> ```
### pushing code
``` git push ```
<br>if branch is not in repo try this command
<br>
``` git push -u origin <branchName> ```


### Undo local commits
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
### Undo pushed commits
``` git revert <commitId> ```

### Rebase
``` git rebase <branch A> <branch B> ```


### Revert Rebase
``` git rebase --abort ```


### Amend most recent commit
``` git commit --amend ```
