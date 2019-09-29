---
title: 在GitHub上搭建自己的博客网站
date: 2019-09-29 21:24:14
tags: github,web,博客
categories: 实战篇
---
#####1.工具准备

node.js、GitHub账号以及一个可以用的顺手的文件编辑器（因为要修改一些配置文件）
node.js安装好后在命令行键入：

				npm -v
来检测环境是否安装完成。
					
#####2.安装hexo博客框架

命令行键入：

				npm  install -g hexo-cli
安装完成之后确保环境变量配置正确，可以正常使用'hexo'命令。

#####3.开始搭建，初始化项目

首先命令行转到你要建立项目的磁盘，然后键入：

				hexo init {projectname}
现在目标磁盘就有了刚才我们新建的项目文件夹，进入项目根目录输入：

				hexo generate
对hexo编译成HTML代码，然后输入：

				hexo server
现在项目就运行起来了，打开输出的本地网址就能看到项目运行的效果了。
![enter description here](./images/Snipaste_2019-09-29_22-01-49.png)