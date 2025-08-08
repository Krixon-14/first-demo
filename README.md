# first-demo
Hello everone .
# clone - 
git clone <-some link->
# satus -
git status
# add - adds new or changed file in your working directory to the git staging area.
git add <- filename->
# commit - it is the record of change
git commit -m "some message"
# push - upload local repo content to remote repo
git push origin name
# init - used to create a new git repo
git init
-> git remote add origin <-link-> (to add new file from vs to new repository)
-> git remote -v (to verify remote)
-> git branch (to check branch)
-> git branch -M main (to rename branch)

-> git checkout <-branch name-> (to navigate)
-> git checkout -b <-new branch name-> (to create new branch)

=>git branch -d <-branch name-> (to delete branch)

=>git diff <-branch name-> (to compare commits , branches, files & more)
=>git merge <-branch name-> (to merge 2 branches)

=> git pull origin main :- used to fetch and download content from a remote repo and immediately update the local repo to match that content

=> case 1: staged changes
           git reset <-file name-> or git reset
   case 2: commited changes (for one commit)
           git reset HEAD~1 (pointer to last commit)
   case 3: commited changes(for many commits)
           git reset <-commit hash->
           git reset --hard <-commit hash->
          
   