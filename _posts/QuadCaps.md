---
layout:     post
title:      QuadCaps
subtitle:  QuadCaps 是一个Cinema 4D插件，帮助用户闭合多边形孔四边形网格，而不创建Ngons
date:       2018-06-06
author:     Brywmzl
header-img: img/C4D/csm_gits_video_top_770493397e.jpg
catalog: true
tags: [C4D插件]
---
QuadCaps 是一个Cinema 4D插件，帮助用户闭合多边形孔四边形网格，而不创建Ngons

<!--more-->

![](/img/C4D/plug-ins/QuadCaps/quadcaps.jpg)  

# 下载
> [官方主页](http://www.c4dzone.com/en/shop/plug-ins-17/quadcaps-1-0-255.htm)
> [网盘下载](https://pan.baidu.com/s/1skEWB4D#list/path=/App/MAXON/_Plug-ins/QuadCaps&parentPath=/App)

# 安装说明
* 将 `QuadCaps_en` 里面的 `quadcaps` 文件夹拷贝到 `plugins` 文件夹下
* 将 `Quad_Caps_1.0_KG` 文件夹拷贝到 `plugins` 文件夹下
* 启动CINEMA 4D，打开插件菜单下选择 `QuadCaps Kengen` 弹出许可文件生成窗口，点击 `Generate youe license` ，弹出序列号窗口，右键复制序列号
* 插件菜单下选择 `Reload Python Plugin` 弹出插件注册窗口，粘贴序列号，点击 `Activate youe license` ，就可以激活插件了
* 关闭CINEMA 4D，删掉插件目录下的`Quad_Caps_1.0_KG` 文件夹，开启CINEMA 4D，就可以看到QuadCaps插件了

# 使用说明
{% vimeo 83837885 %}

* QuadCaps
	* 用于封闭偶数个边闭合孔洞
* Uneventoeven
	* 当边数为奇数（使用 Quadcaps 提示"Selected edges must be even" 因此不能封闭）Uneventoeven 可以将一个面变成三角形从而得到偶数边


**QUADCAPS 插件**

QuadCaps 是一个 Cinema 4D 插件，帮助用户闭合多边形孔四边形网格，而不创建 Ngons。
插件的工作原理非常简单：

1）选择边缘环关闭  
2）调用四方工具。






多边形将用四边形网格封闭。



  
如果你想改变开始构造点，只需在使用 QuadCaps 之前留下一个选定的点，选择的点将被用来开始创建封顶。



  
你可以闭合环只有偶数的边缘，并为最佳性能的工具关闭伪规则孔。  
但是，如果您需要闭合不平整的循环边缘，我们已经发布了另一个减少边缘数量的工具，但是它会创建一个三角形。  
这个插件适用于所有版本的 Cinema 4D （Prime，Broadcast，Visualize，Studio）以及所有与 Cinema 4D 兼容的引擎渲染器（V-Ray 等）。

原文~~~

**QUADCAPS PLUGIN**

QuadCaps is a Cinema 4D plugin that helps user to close polygon hole with quadrangular mesh without creating Ngons.  
The plugin's working principle is very simple:  

1) Select the edge loop to close  
2) Call QuadCaps tool.  

The polygon will be closed with a quadrangular mesh  
If you want to change the start construction point just leave a selected point before using the QuadCaps tool, selected point will be used to start the creation of the cap.  
You can close loop only with even number of edges and for a best performance of the tool close pseudo regular hole.  
However if you need to close an uneven loop edge we have released another tool that reduces the number of edges but it will create a triangle.  
The plugin works with all editions of Cinema 4D (Prime, Broadcast, Visualize, Studio) and with all cinema 4D compatible engine renderers (V-Ray etc).  
