# git 101
```
git init
git status
git status --short
git add
git add --all
git add -A
git commit -m "MSG"
git commit -a -m "MSG"
git log
git CMD -help
git CMD --help
git help -all
git branch NEW_BRANCH       # create new branch
git branch                  # show available branch
git branch -a               # show all branch
git branch -r               # show remote branch only
git checkout NEW_BRANCH     # change working branch
git checkout -b BRANCH      # change working branch, create new branch if it is not exist
git merge EMERGENCY_FIX     # merge down the EMERGENCY_FIX branch to current working branch
git branch -d EMERGENCY_FIX # delete EMERGENCY_FIX branch
git remote add origin URL
git pull
git fetch origin
git diff origin/main
git merge origin/main
git push origin main        # Push up "main" local to "origin" remote repo

```