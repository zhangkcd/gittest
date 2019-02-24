1、git_bash.exe
2、ssh-keygen -t rsa -C "kaichun2008@163.com"
3、ssh -T git@hub.com

--set config
git config --global user.name zhangkcd
git config --global user.email kaichun2008@163.com
git config --list #show config list

git init
git add .
git add readMe.txt

git commit -m "new file commit"
git diff readMe.txt
######
git status
git log
git log --pretty=oneline
git remote add origin https://github.com/zhangkcd/gittest.git
git pull origin master --allow-unrelated-histories
git push -u origin master

