#lab2 versionControl 

git --version

git config --global user.name "Abdallah Sayed"
git config --global user.email "abdallah2001.sayed@gmail.com"
git config --list
apt-get install git
sudo apt-get install git
ssh-keygen -t ed25519 -C "lab1"

//cat /home/electronica/.ssh/id_ed25519
cat ~/.ssh/id_ed25519.pub
git init
git status
git add index.html
git commit -m "first commet"
git remote add origin	
git@github.com:AbdAllahSayed11/lab1control.git
git remote add origin git@github.com:AbdAllahSayed11/lab1control.git
 git remote add origin
 git commit -m "second commet"
 git push -u origin master
 
 git branch -m master main
git push origin main
git push origin --delete master
