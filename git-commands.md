# Git commands
+ -setup & config
   + git init <filename>
   + git clone <url>
   + git config --global "username"
+ workflow
   + git add <filename>
   + git commit -m "message"
+ Viewing Changes
   + git status
   + git log 
## what it does??
+ git init - helps to initialize new git repository 
+ git clone - helps to create a local copy of an existing git repository
+ git config --global "username" - it manages configuration operation for git enviroment
+ git add - it adds the working direcotry to stageing area
+ git commit -m "message" - save the snapshot of project/repo
+ git status - to monitat the state of repo or working direcotry
+ git log - it use to see the history of commit
+ git merge - use to intigrate the changes from seprate branch
+ git rebase - this will take commits from your current branch and replays them on top of anothr branch
+ git reset --soft HEAD~1 - it removes the comit ,but keeps the changes staged
+ git reset --mixed head~1 - commits from your current branch and replays them on top of anothr branch
+ git reset --hard head~1 - it delete the commit and make working direcotry clean
+ git revert <commit id> - git revert does not commit that undoes the changes ,keep history safe 

