# IBM_capstone_projects
This repository consists of IBM Data Science course capstone project material
mkdir ~/Desktop/projects
cd ~/Desktop/projects
ls
git init
git remote add origin <githubclonelinkpastehere>
git remote -v
git add .
git commit -m "makeanycomment"
git push origin master

# if the above doesn't work then run the below code:
git fetch origin master:tmp
git rebase tmp
git push origin HEAD:master
git branch -D tmp
