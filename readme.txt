hello world!
Git is a distributed version control system.
Git is free software.

====================================

git config --global name="" 
git config --global email=""
//初始化
git init

//添加到仓库
git add 'file.txt'

//提交并赋予提交信息
git commit -m "add message status"


//查看提交状态
git status 

//查看不同
git diff 

//查看提交的历史日志
git log
git log --pretty=oneline //简化版

//，在Git中，用HEAD表示当前版本