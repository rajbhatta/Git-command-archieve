### 1. Delete remote branch ###
```js
git push origin --delete branch_name
```

### 2. How to merge remote branch ###
Let us consider we do have develop(running inside IDE) and master(located inside remote git)
```js
git checkout master
git pull
git checkout develop
git merge master
```

### 3. How to do a force push ###
```js
git log -n 10
git reset commit-number(get commit number from log)
git push origin branch_name -f
```

### 4. How to list all branch in gitHub ###
```js
git branch -a 
```

### 5. How to delete a git commit using rebase ###
```js
1. HEAD ~1 (Where ~1 represents the last one commit from the head).
2. Head ~2 ( where ~2 represetns the last two commit from the head).

git reabase -i HEAD~3 (where i represents the interactive).

It will open in the vim edition. Press i to goto insert mode

change pick 18c2(sample commit number) to Drop 18c2

Type Esc:wq

```

### 6. How to rename git branch ###
```js
git branch -m newName

git push origin :oldName newName

Note: if we create a PR then name of the branch will be there.
```
