+++
title = "Servers"
slug = "Servers"
date = "2024-06-25"
series = ["Theme Demo"]
+++

现在正在使用的服务器
```bash
#跳转服务器
cityu3:
yangjs@144.214.24.236

cityu4:
yangjs@144.214.25.9

#cityu6硬盘待安装
cityu6:
yang@144.214.24.125

cityu7:
yangjs@144.214.25.165

cityu8:
yang@144.214.25.79

cityu15:
yang@144.214.24.149

sz1:
-p 30274 yjs@211.99.98.122
#or
-p 30274 yjs@s7.z100.vip

#vscode Host
Host cityu15
    HostName 144.214.24.149
    User yang
    ForwardAgent yes
    ProxyCommand ssh -W %h:%p cityu3
    IdentityFile "C:\Users\84591\.ssh\id_rsa"

```