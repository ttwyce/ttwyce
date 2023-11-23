---
title: "Termux安装使用git"
date: 2023-08-30T18:00:16Z
description: "Lorem Ipsum Dolor Si Amet"
tags:
- termux
- git教程
- 折腾
categories:
- termux
share : true  # 是否开启分享
---
开始安装git

``` bash
pkg install git
```


配置一下用户信息

``` bash
git config --global user.name "你的git用户名"
git config --global user.email "注册git使用的邮箱"
```

安装ssh
``` bash
pkg install openssh
```

报错可以尝试安装一下openssl
``` bash
pkg install openssl
```

生成key
``` bash
ssh-keygen -t rsa -C "注册git使用的邮箱"
```