GitHub Ultimate Master Git and GitHub - Beginner to Expert
#Training 

Change "origin" ==> master (or another main name for remote push

## EXAMPLE
git remote add master https://github.com/xyz/cms-demo.git
git branch -M main
git push -u master main


pwd Command ==> current directory PATH
git init		(Need To Be Inside Working Directory)
git add .
git commit -m “message text goes here”
git add -u
git add -A
git checkout -b updates
git commit -am “express commit”		(Express Commit)
git diff updates master
ls -al
git checkout -b updates
git checkout -b thebranchname
pwd
git config --global alias.hist "log --oneline --graph --decorate --all"
touch .gitignore 
mate  .gitignore     	(Add *.log, .DS* Note: 1 per line)


git status
git branch
git checkout master
git merge updates
git branch -d updates
git commit -m "Adding example file"
git mergetool
git tag taglabelexamplename
git tag —list
git stash
git reset  e786sc  —soft   	(—mixed, —hard)    
