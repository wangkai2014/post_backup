---
layout:     post
title:      PuTTY
subtitle:  一个轻巧的终端
date:       2018-01-21
author:     Brywmzl
header-img: img/post-bg-hacker.jpg
catalog: true
tags: [PuTTY,终端]
categories: [网络工具]
---
一个轻巧的终端

<!--more-->

[官方网站](https://www.putty.org/)  

# 下载
> [官方下载](https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html)  
> [网盘下载](https://pan.baidu.com/s/1eTl4Avo)  

# 极路由安装 Shadowsocks
* 安装Shadowsocks插件之前需要先开通开发者权限，可以参考[官方教程](http://jingyan.baidu.com/article/4f7d5712ca0d031a21192779.html)
* 安装开发者插件：“云插件”>“全部插件”>“开发者模式”>”确定”。

![](/img/PuTTY/0.png)  
* 运行putty,看到如下界面，输入 Host Name:`192.168.199.1` Port:`1022` 点击 Open

![](/img/PuTTY/1.png)  
* UserName:`root` Password：`后台登录密码`（密码右键静默粘贴不会显示）

![](/img/PuTTY/2.png)  
* 一键安装脚本（支持最新1.4.5.19222s固件）
```
cd /tmp &&curl -k -o shadow.sh https://raw.githubusercontent.com/qiwihui/hiwifi-ss/master/shadow.sh && sh shadow.sh && rm shadow.sh
```
* 复制后 右键粘贴

![](/img/PuTTY/3.png)
* 注意！！！
	* 插件在路由器系统升级后会消失，请把自动升级改为手动升级。
	* 请不要恢复路由器出厂设置，否则插件也会消失。

![](/img/PuTTY/4.png)  
[原文](http://blog.sina.com.cn/s/blog_4891cbc50102wnm3.html)
