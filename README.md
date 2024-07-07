# lab Version Control
## Members
1. Mohamed Shahin
2. Marwan Khaled
3. Assmaa Ibrahim
4. Ahmed Ehab
## Installing
```
# downloading the project
git clone https://github.com/mohamedshahin-10/Version_Control-_Lab1.git
```
## How to merge code from different branches into the main branch
1. create branch
```
git branch BranchName
```
2. switch to branch
```
git switch branchName
```
3.Make modifications on your local branch and then push these changes to your remote branch.
```
git add .
git commit -m "your commit message"
git push --set-upstream origin BranchName
```
4. switch to main
```
git switch main
```
5. Merge your branch into the main branch
```
git merge branchNmae main
git push
```
