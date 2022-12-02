---
title: 记一次曲折的qemu安装历程
date: 2022-06-15 14:33:31
tags:
  - archlinux
  - 教程
  - Github
---

# 记一次曲折的qemu安装历程

之前一直用Parallels Desktop安装的Ubuntu，但是作为一个arch党，这很难受，但是在百度上搜到的结果嘛...

![image-20220615143848598](https://raw.githubusercontent.com/myp0402/BlogComment/main/imagesimage-20220615143848598.png)

~~（当场去世）~~

第一个结果我看了一下，竟然要自己先准备一个Linux，然后借助那个Linux去在虚拟硬盘上安装ArchLinuxARM，导出成虚拟硬盘文件，再扔到mac上用qemu启动，这个流程，主要是因为arch的arm版并没有iso镜像，所以只能这么装
