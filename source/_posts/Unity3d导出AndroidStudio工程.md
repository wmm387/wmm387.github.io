---
title: Unity3d导出AndroidStudio工程
date: 2017-11-03 11:46:29
tags:
	- Unity3d
	- Android
---
关于Unity3d与Android之间的调用,可以通过两种形式,一个是将Android的java代码打包成jar文件导入Unity3d工程中,还有一种就是将Unity3d工程导出为Android工程,在Android IDE中二次编辑.

本文主要写将U3d导出为Android工程,并在Android Studio中打开编写.
---
## Unity3d导出android工程

### 创建u3d工程

新建一个u3d工程,并创建一个cs脚本Test.cs,绑定在摄像机上,其为主页面,并在页面上创建3个按钮,如下图所示

![u3d页面](../images/u3d01.png)