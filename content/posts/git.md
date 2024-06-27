+++
authors = ["Yang Jiansong"]
title = "The usage of git"
date = "2024-06-26"
description = "Construction time and method"
tags = [
    "hugo",
    "markdown",
    "git",
]
categories = [
    "syntax",
    "theme demo",
]
series = ["Theme Demo"]
+++
使用方法: git

```bash
#第一次
git init
git remote add origin https://github.com/yourName/repositoryname.git

#非第一次
#add命令添加所有文件到临时库
 git add .
#commit命令添加修改的文件到本地库
 git commit -m "new commit"
#push命令将本地库文件上传到远程库
 git push -u origin master

 #也可以直接使用我编写好的脚本update_git.sh
 bash update_git.sh

 #删除连接
 ```