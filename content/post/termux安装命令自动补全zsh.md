---
title: "Termux安装命令自动补全zsh"
date: 2023-08-31T11:13:45Z
tags:
- termux
- 折腾
categories:
- termux
share : true  # 是否开启分享
---

## Termux介绍
Termux是一款强大的终端模拟器，可以在Android设备上运行各种Linux命令。如果想要在Termux中实现代码自动补全，可以使用一些特定的工具，如fish shell或zsh ，这里主要介绍zsh。
## zsh 介绍
zsh 是一个兼容 bash 的 shell，相较 bash 具有以下优点：

- Tab 补全功能强大。命令、命令参数、文件路径均可以补全。
- 插件丰富。快速输入以前使用过的命令、快速跳转文件夹、显示系统负载这些都可以通过插件实现。
- 主题丰富。
- 可定制性高。
关于 zsh 的更多的信息，可以访问  [zsh.org](https://www.zsh.org/ "zsh.org")查看

## 安装 zsh
在Termux中安装zsh，可以执行以下命令：
``` bash
pkg install zsh
```
第一次安装后可能需要手动启动一下zsh
直接在终端执行zsh命令就可以启动zsh如下：
```bash
zsh
```
在启动后，就可以使用一些命令实现代码自动补全功能，例如：
![例如](images/Screenshot_20230831-190727351.jpg)