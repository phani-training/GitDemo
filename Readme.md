# Git Commands
- - First create a local repo which is in UR machine
- git status
- git init -It creates a git hidded dir
- 
- rmdir -force .git ->To remove the directory. 
- git init -b main ->creates a main braing. 
- git add fileName
- git status ->tracks the changes and gives updates. 
- git commit -m "test info"
- git log ->gets the info about the commits.
- 
- git commit-a -m "mythird commit" ->goes to commit without staging.
- 
- git diff ->will tell the differences in the code.
- git diff --staged ->tells the differences in the staging area. 
- git rm --cached .\creds.txt ->removes a file from the git.
- 
## Pulling to the git hub:
- Have an account on git hub
- git clone address of the git repo 

## Adding existing repo into git hub:
- Create a new Repo in the github account
- Run the following commands from the git local repo
``` 
git remote add origin https://github.com/phani-training/GitDemo.git
git branch -M main
git push -u origin main
```

## Adding branches:
- To create a new branch: git checkout -b feature1
- To see all branches: git branch
```
git checkout -b feature1
git add newFiles
git commit -m "adding to branch"
git push -u oring feature1

```
