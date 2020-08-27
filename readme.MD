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
