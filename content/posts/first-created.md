+++
authors = ["Yang Jiansong"]
title = "Construction time and method"
date = "2024-06-25"
description = "Construction time and method"
tags = [
    "hugo",
    "markdown",
    "emoji",
]
categories = [
    "syntax",
    "theme demo",
]
series = ["Theme Demo"]
+++

我是用**Hugo**进行的本网站搭建。
```bash
#hugo版本
$ hugo version
hugo v0.127.0-74e0f3bd63c51f3c7a0f07a7c779eec9e922957e+extended windows/amd64 BuildDate=2024-06-05T10:27:59Z VendorInfo=gohugoio

#hugo搭建新网站
$ hugo new site <sitename>
$ cd <sitename>
#hugo主题
$ cd themes
$ git clone https://github.com/luizdepra/hugo-coder.git 

#将exampleSite文件夹下的所有文件复制到<sitename>文件夹下
#返回<sitename>文件夹，使用Hugo命令搭建随时查看的本地网站
$ hugo server --disableFastRender

#使用hugo更新public文件夹
$ hugo
```
基于**Github**托管的网站

```bash
#永久域名
yang-jiansong.github.io
#快速境外域名
https://yangjiansong.vercel.app/
#将public下的所有文件上载到github yang-jiansong.github.io仓库中
https://github.com/YANG-JIANSONG/YANG-JIANSONG.github.io
```

