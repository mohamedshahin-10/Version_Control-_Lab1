# lab Version Control
## Members
1. Mohamed Shahin
2. Marwan Khaled
3. AssmaaIbrahim
4. Ahmed Ehab
5. Nooran Amr
## How to do merge form different branches to main
1. create branch
   ```
   git branch branchName
   ```
2. switch to branch
  ```
  git switch branchName
  ```
3. Make modifications on your branch and then implement these changes to your remote branch.
```
git add .
git commit -m "your commit message"
git push --set-upstream origin branchName
```
4. switch to main
```
    git switch main
```
6. merge your branch to main
```
git merge branchNmae main
git push
```
 
 
 
