# Document Git

## Create branch
```
git branch <branchname>
```
## Switch branch
```
git checkout <branchname>
```
## Delete branch
```
git branch -D <branchname>
```
## Commit branch
````
B1. git add <file-name-1> <file-name-2> <file-name-3>
B2. git reset HEAD <file-name-1> <file-name-2> <file-name-3>
B3. git commit -m "<message commit>"
B4. git push -u origin <branchname>
````
## Reset branch
````
B1. git reset <parents>
B2. Edit file
B3. git commit -m "<message commit>"
B4. git push -u origin <branchname> -f
````
## Rename branch
````
B1. git checkout -b <branchname>
B2. git branch -m <branchname_new>
B3. git push origin :<branchname> <branchname_new>
B4. git push origin -u <branchname_new>
````
## Conflict branch
````
B1. git fetch origin
B2. git checkout -b <branchname> origin/<branchname>
B3. git merge <branch-master>
B4. Edit conflict
B5. git commit -m "<message commit>"
B6. git push -u origin <branchname>
````
## Merge branch
````
B1. git checkout <branch-master>
B2. git merge --no-ff <branchname>
B3. git push origin <branch-master>
````