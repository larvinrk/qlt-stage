Hiii my sample txt file.

git init qt_stage --- add folder to git respostary

git status. --- to chech the status of respostary
git add <file-name> --- to add file to stage env. 
git commit -m "cmmit msg" --- to commit to live(meas)


git init . -- adding existing folder to git respostary

git add . -- will add all files to stage ennv.

git commit . --will commit all 

git log --oneline --graph --decorate --all

git mv smaple.txt demo.txt. -- rename file in respostary
git staus

git commit -m "renamed"

git rm demo.txt -- to del a file 

To ignore files need to create .gitignor file and add what are the files needs to ignored for commit.
-------

git mate .gitignor
  -- add file name need to igonre ex all log files *.log
git add .gitignor 
git commit -m "adding .gitignoer"

-------Create Branches---

git checkout -b <branchupdate> --- Create branch and switch to it

git add . -- Adding modified file to that branch.
git commit -m "adding update to branch"

updates for only branch 

***** git log --oneline --graph --decorate --all  -----to see the all changes 

*** To Merge branch to master/trunk we need to switch to master then we need to use merge command. 
git merge <branchname> -- it will merge to master

get branch -d <branchname> ---to delete the branch.

*for bad for confilict*******


git reset --Soft <commitid> ----It will only point head ot that commit id, again we need to comit and add.
git rest --hard <commitid> -----It will point commit and addtoo

----------------------------------------GIT HUB---------------------





