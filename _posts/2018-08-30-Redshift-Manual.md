---
layout:     post
title:      Redshift 笔记
subtitle:   https://docs.redshift3d.com/display/RSDOCS
date:       2018-08-30
author:     Brywmzl
header-img: img/RedShift/261331074269.jpg
catalog: true
tags: [CINEMA 4D,Redshift]
password: 
---
https://docs.redshift3d.com/display/RSDOCS

<!--more-->

# [Cameras（摄像机）](https://docs.redshift3d.com/display/RSDOCS/Cameras)

# [Shader（着色器节点）](https://docs.redshift3d.com/display/RSDOCS/Shaders)

## [Material Shaders（材质）](https://docs.redshift3d.com/display/RSDOCS/Material+Shaders)

## [Textures Shaders（纹理）](https://docs.redshift3d.com/display/RSDOCS/Noise+Texture)

### Color
This tab allows you to control how the internally computed noise is turned into color for output.
这个标签允许你控制内部计算的噪波如何转换为输出颜色。

### Noise
This tab allows you to control how the noise is generated.
这个标签允许你控制噪波的生成。

#### General（通用）
* Noise Type（噪波类型）
	* Fractal（分形）
	* Turbulence（湍流）
	* Cell（蜂窝）

#### Fractal/Turbulence（分形/湍流）
* Complexity（复杂）
* Amplitude Gain（振幅增益）有点像羽化
* Frequency Scale（频率缩放）就是缩放
* Distortion（失真）好像是扭曲又好像移动
* Distortion Scale（失真缩放）

#### Time

##### Source（源）

Allows you to control how the noise is affected over time. The options are as follows:
* None - 不考虑时间计算
* Constant（常量） - 当前帧时间来计算
* User - 用户定义的时间来计算

##### Constant
这是应用于当前帧时间的比例。仅在Source设置为“常量”时适用

##### Consant Scale
This is a scale that is applied to the current frame time. Only applicable when Source is set to 'Constant'.

##### User Time
This is the user-defined time value. Only applicable when Source is set to 'User'.

## Color

### Color Layer