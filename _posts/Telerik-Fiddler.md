---
layout:     post
title:      Telerik Fiddler
subtitle:   最专业的网络调试工具
date:       2018-01-05
author:     Brywmzl
header-img: img/Fiddler/banner_promotional_section.png
catalog: true
tags: [Telerik Fiddler]
categories: [网络工具]
---
最专业的网络调试工具

<!--more-->

[官方网站](https://www.telerik.com/fiddler)  

# 下载
> [官方下载](https://telerik-fiddler.s3.amazonaws.com/fiddler/FiddlerSetup.exe)  
> [网盘下载](https://pan.baidu.com/s/1pK8p2xt)  

# 开启 Https 抓包
![](/img/Fiddler/3.gif)  

* `Tools`->`Fiddler Options`->`Connections`
* `Fiddler listens on port`（监听端口） 默认`8888`
* 勾选`Allow remote computers to connect`（允许远程发送请求）
* `Tools`->`Fiddler Options`->`HTTPS`
* 勾选`Decrypt HTTPS traffic`（解析HTTPS流量），抓https请求必须安装证书

![](/img/Fiddler/0.png)  
* http://`PC端在局域网的IP`:`Fiddler listens on port`（监听端口）
* 鼠标经过右上角的`Online`可以看到IP

![](/img/Fiddler/1.png)  
* 勾选`Allow remote computers to connect`（允许计算机运程连接）
* 设置完重新打开 Fiddler 才能访问

![](/img/Fiddler/2.png) 
* 手机设置HTTP...此处略去

## 开启/关闭 抓本机的包
![](/img/Fiddler/5.png)  
* 1.只需要启动程序并确保左下角为 Capturing状态 即可。
* 2.按快捷键 F12 进行切换。  

![](/img/Fiddler/6.png)  
* 3.File –> Capture Traffic 勾选。  

这个很有用，可以开启抓本机的包，也可以过滤本机的包。当手机开启了开启了代理，就可以把本机的包过滤掉，专注抓手机的包，此时会话列表中都是手机的包了。  
[原文](https://blog.csdn.net/zhaoyanjun6/article/details/72956016)  

## 抓包过滤
![](/img/Fiddler/4.png)  
* `from all processes` : 抓取所有的 https 程序, 包括 本机 和 手机
* `from browsers only` : 只抓取浏览器中的 https 请求
* `from non-browsers only` : 只抓取除了浏览器之外的所有 https 请求
* `from remote clients only` ： 抓取远程的客户端的 https ,可以代表手机