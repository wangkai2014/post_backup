---
layout:     post
title:      KeyShot
subtitle:   惊艳的视觉效果 快速的实时渲染
date:       2018-10-12
author:     Brywmzl
header-img: img/keyshot/keyshot-7-viewer-section-04.jpg
catalog: true
tags: [Keyshot]
categories: [渲染引擎]
---
惊艳的视觉效果 快速的实时渲染

<!--more-->

![](/img/keyshot/Integration_Splash_2016.png)

{% youtube I14ndjM__bY %}

[官方网站](https://www.keyshot.com/)
[实例场景](https://www.keyshot.com/resources/downloads/scenes/)
[KeyShot Plugin Manuals](https://luxion.atlassian.net/wiki/x/WQ5JAg)  
[KeyShot Plugin Downloads](https://www.keyshot.com/resources/downloads/plugins)  
[KeyShot 8 Manual](https://luxion.atlassian.net/wiki/spaces/K8M/)
[KeyShot 7 Manual](https://luxion.atlassian.net/wiki/spaces/K7M/)

# 下载
> [最新版本](https://www.keyshot.com/try/)
> [以前版本](https://www.keyshot.com/resources/downloads/previous-versions/)
> [网盘下载](https://pan.baidu.com/s/1geOKjXx)  

**Previous KeyShot versions**

|Versions|Windows 32-bit|Windows 64-bit|Mac OS X|
|:-:|:-:|:-:|:-:|
|v8||[keyshot_w64_8.0.247.exe](https://s3.amazonaws.com/download.keyshot.com/keyshot8/keyshot_w64_8.0.247.exe)|[keyshot_mac64_8.0.247.pkg](https://s3.amazonaws.com/download.keyshot.com/keyshot8/keyshot_mac64_8.0.247.pkg)|
|v7||[keyshot_w64_7.3.40.exe](https://s3.amazonaws.com/download.keyshot.com/keyshot7/keyshot_w64_7.3.40.exe)|[keyshot_mac64_7.3.40.pkg](https://s3.amazonaws.com/download.keyshot.com/keyshot7/keyshot_mac64_7.3.40.pkg)|
|v6|[keyshot_w32_6.3.23.exe](http://s3.amazonaws.com/download.keyshot.com/keyshot_w32_6.3.23.exe)|[keyshot_w64_6.3.23.exe](http://s3.amazonaws.com/download.keyshot.com/keyshot_w64_6.3.23.exe)|[keyshot_mac64_6.3.23.pkg](http://s3.amazonaws.com/download.keyshot.com/keyshot_mac64_6.3.23.pkg)|
|v5|[keyshot_w32_5.3.6.exe](http://download.keyshot.com/keyshot_w32_5.3.6.exe)|[keyshot_w64_5.3.6.exe](http://download.keyshot.com/keyshot_w64_5.3.6.exe)|[keyshot_mac64_5.3.6.pkg](http://download.keyshot.com/keyshot_mac64_5.3.6.pkg)|
|v4|[keyshot_w32_4.3.18.exe](https://s3.amazonaws.com/download.keyshot.com/keyshot_w32_4.3.18.exe)|[keyshot_w64_4.3.18.exe](https://s3.amazonaws.com/download.keyshot.com/keyshot_w64_4.3.18.exe)|[keyshot_mac64_4.3.18.pkg](https://s3.amazonaws.com/download.keyshot.com/keyshot_mac64_4.3.18.pkg)|
|v3|[keyshot_w32_3.3.33.exe](https://s3.amazonaws.com/download.keyshot.com/keyshot_w32_3.3.33.exe)|[keyshot_w64_3.3.33.exe](https://s3.amazonaws.com/download.keyshot.com/keyshot_w64_3.3.33.exe)|[keyshot_mac64_3.3.33.pkg](https://s3.amazonaws.com/download.keyshot.com/keyshot_mac64_3.3.33.pkg)|
|v2|[keyshot_w32_2.3.2.exe](https://s3.amazonaws.com/download.keyshot.com/keyshot_w32_2.3.2.exe)|[keyshot_w64_2.3.2.exe](https://s3.amazonaws.com/download.keyshot.com/keyshot_w64_2.3.2.exe)|{% raw %}{% endraw %}|

* 更新包只需在下载文件名后面加`_update`（不包含扩展名）  

---

**Content Download**

|Versions|Windows|Mac OS X|
|:-:|:-:|:-:|
|KeyShot 8|[keyshot_resource_installer.exe](https://s3.amazonaws.com/download.keyshot.com/keyshot8/keyshot_resource_installer.exe)|[keyshot_resource_installer.pkg](https://s3.amazonaws.com/download.keyshot.com/keyshot8/keyshot_resource_installer.pkg)|
|KeyShot 7|[keyshot_resource_installer.exe](https://s3.amazonaws.com/download.keyshot.com/keyshot7/keyshot_resource_installer.exe)|[keyshot_resource_installer.pkg](https://s3.amazonaws.com/download.keyshot.com/keyshot7/keyshot_resource_installer.pkg)|

---

**Content Installation**
After downloading, run the installer. During installation, the new resources will be added to your KeyShot Resource folder and visible in the KeyShot library, Materials tab. The new Poliigon folder will be added to your Materials folder.

下载后，运行安装程序。在安装过程中，新资源将添加到KeyShot Resource文件夹中，并在KeyShot库的Materials选项卡中可见。新的Poliigon文件夹将添加到您的Materials文件夹中。

# KeyShot8 安装说明

And install instruction:

1. Install Luxion KeyShot® 8.0.247

2. Open the ‘Patch’ folder and highlight|copy the two files: ‘keyshot8.lic’ and ‘keyshot8_extras.lic’. Paste the two copied files into: C:\Users\%username%\Documents\KeyShot 8

3. Right click Notepad and ‘Run as administrator’. File > Open ‘hosts’ located in: C:\Windows\System32\drivers\etc\
Add the following two lines:
```
127.0.0.1 proxy8a.luxion.com
127.0.0.1 proxy8b.luxion.com
```

4. From the ‘Patch’ folder copy the Patcher ‘lkeyshot8-tpc-patch.exe’ and paste it into the KeyShot 8 installation folder [default location: C:\Users\%username%\AppData\Local\KeyShot8\bin]

5. Run ‘lkeyshot8-tpc-patch.exe’ and when prompted, enter the password: tpcrew-group [Proceed]. Click ‘Patch’ and once patch complete, select ‘Exit’

6. The Patcher will have created another ‘bin’ folder within ‘bin’ [C:\Users\%username%\AppData\Local\KeyShot8\bin\bin]. Inside the new ‘bin’ folder, copy the patched ‘keyshot.exe’ file.

7. Return to the installation folder [C:\Users\%username%\AppData\Local\KeyShot8\bin] and paste and replace the existing ‘keyshot.exe’ file

8. Done!

# KeyShot7 安装说明
* 1.安装 KeyShot，装完后关闭安装程序，不要运行 KeyShot
* 2.复制补丁 `keyshot.exe` 到 KeyShot 安装目录，替换文件
![](/img/keyshot/0.jpg)
* 3.打开注册机 `Keygen.exe`，点击 `Generat` 生成.lic许可证文件
![](/img/keyshot/1.jpg)
* 4.运行 KeyShot，选“安装许可证文件(*.lic)”，下一步，选择刚刚生成的.lic许可文件，点完成！
