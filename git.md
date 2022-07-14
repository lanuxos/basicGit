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
git merge origin/main       # merge main branch to origin branch
git push origin main        # Push up "main" local to "origin" remote repo
git remote -v
git remote rename ORIGIN NEW_NAME # rename remote repo [ORIGIN] to NEW_NAME
git remote add origin URL
.gitignore
ssh-keygen -t rsa -b 4096 -C "test@la.com"
ssh-add /Users/user/.ssh/id_rsa
clip < /Users/user/.ssh/id_rsa.pub  # clip < command, use to copy to clipboard
ssh -T git@github.com
git remote add ssh-origin git@github.com:w3schools-test/hello-world.git
git remote set-url remote-name git@github.com:username/repository.git
git log --oneline
git revert HEAD --no-edit   # revert to HEAD commit
git revert HEAD~1
git reset COMMIT_HASH
git commit --amend -m "RE-WRITE TO LAST COMMIT COMMENT"
```