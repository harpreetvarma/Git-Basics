# Git-Basics
My Learning On Git Basic's to Get Through


 git branch MyBranch
git checkout MyBranch
touch file.css
git add .
git commit -m 'new changes done'
git checkout master
git merge MyBranch
git branch -D MyBranch


ADD a origin(Repo) where we can use command " git push origin master"
git remote add origin "site Link"


touch myfile.txt // added some info here in this file
git commit -a -m 'changes are done in master some info is added to myfile.txt'
git branch MyBranch
git checkout MyBranch
// added changes to myfile.txt now
git commit -a -m 'changes are done in Branch ie MyBranch some info is added to myfile.txt'
git merge master 
// Conflict happened now 
// git made some changes in myfile.txt 
// now i deleted that extra content that git has put in 
git commit -a -m 'merge conflicts now resolved'


git push -u origin master
