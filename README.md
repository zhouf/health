health
======

这是一个测试项目，用于学习GIT的基本使用


简易的命令行入门教程:

Git 全局设置:

git config --global user.name "zhouf"
git config --global user.email "zhouf_t@sohu.com"


创建 git 仓库:

mkdir wther.diagram
cd wther.diagram
git init
touch README.md
git add README.md
git commit -m "first commit"
git remote add origin https://git.oschina.net/mytiger/wther.diagram.git
git push -u origin master


已有项目?

cd existing_git_repo
git remote add origin https://git.oschina.net/mytiger/wther.diagram.git
git push -u origin master