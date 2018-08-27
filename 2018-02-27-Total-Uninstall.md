---
layout:     post
title:      Total Uninstall
subtitle:   戒系一款能帮你监视软件安装过程已经卸载软件的软件。
date:       2018-02-27
author:     Brywmzl
header-img: img/Total_Uninstall/bg.jpg
catalog: true
tags:
    - Total Uninstall
---

[官方网站](https://martau.com)  
[appnee](http://appnee.com/total-Uninstall)  
[Total Uninstall官方视频教程](http://www.martau.com/uninstaller-video-tutorials.php)  
[Total Uninstall命令行选项](http://www.martau.com/document/total-uninstall-command-line.php)  
[http://www.martau.com/document/transfer-programs-to-new-pc.php](http://www.martau.com/document/transfer-programs-to-new-pc.php)

## 下载
>- [官方下载](https://www.martau.com/uninstaller-download.php)
>- [网盘下载](https://pan.baidu.com/s/1jJBMB22)

## 安装说明
* 断网！！！
* 用户名：`Any Name` （任意名称，不要写中文名）
* 6.22.0 注册码：`87451IN-FP27F04-ZAFL3HKY-YSKJZHO6-PBSW2T6X-YHZRHKDU-JAYC2AQV-ACXFAXOR-B6WOYK2Z-4D52RQY5-IRPQ4EG5-MEBBIUCD-V5ZZM2H7-OIAEWUQX-4APDRTLF-NSA7GOLC`

* 用防火墙阻止`Tu.exe`联网 或 添加 host `%WinDir%\system32\drivers\etc\hosts`
```
127.0.0.1 martau.com
127.0.0.1 total-uninstall.com
```
* user.rule
```
martau.com reject
total-uninstall.com reject
```

## 强制访问网络
* 注册表`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Cryptography`下找到一个项里的值为XXX\\xxxxxxxx数据类型为REG_BINARY的删掉
* 注册表`HKEY_LOCAL_MACHINE\SOFTWARE\Classes\CLSID\{乱七八糟}`下项找值为`ProdID`的删掉

![](https://github.com/Brywmzl/Brywmzl.github.io/raw/master/img/Total_Uninstall/3.png)  
>- [Total_Uninstall_注册反弹清除工具(不支持Win10) 网盘下载](http://pan.ccav1.me/lanzou.php?type=down&url=https://pan.lanzou.com/i0kdgqf)  