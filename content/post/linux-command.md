---
title: "Linux 基本命令"
date: 2023-09-22T14:52:33Z
tags:
- linux
- linux命令
categories:
- linux
share : true  # 是否开启分享
---
## 基本命令

**创建文件夹命令:mkdir**
``` bash
# mkdir www
在当前目录下创建一个www文件夹
# mkdir www/linux/zst -p
同时创建多个文件夹需要加 -p
```

**删除命令:rm**
``` bash
# rm  test.txt 
删除文件test.txt
# rm  -r  home
删除文件可以直接使用rm命令，若删除目录则必须配合选项"-r"
```

删除当前目录下的所有文件及目录，命令行为：`rm  -r  *`

文件通过rm命令删除 则无法恢复 请三思而后行
