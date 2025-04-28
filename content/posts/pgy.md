+++
authors = ["Yang Jiansong"]
title = "Oray software installation"
date = "2024-08-25"
description = "Construction time and method"
tags = [
    "Oray",
    "markdown",
    "connext",
]
categories = [
    "syntax",
    "theme demo",
]
series = ["Theme Demo"]
+++


```bash
#下载蒲公英软件
wget https://pgy.oray.com/softwares/153/download/2156/PgyVisitor_6.2.0_x86_64.deb
sudo -s
dpkg -i PgyVisitor_6.2.0_x86_64.deb

#使用方法
pgyvisitor login
orkj8312383hli3b

-h --help help
-v --version get version

These are common pgyvisitor commands used in various situations:

login         login
logout        logout
logininfo     display historical login device information
autologin     set auto login
certcheck     enable or disenable certificate verification
bypass        display bypass infomation
getmbrs       display vpn networking and members information
showsets      display setting information

#管理网站
https://console.sdwan.oray.com/zh/main
 ```