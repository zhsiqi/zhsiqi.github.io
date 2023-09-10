---
title: macOS查看外接移动硬盘通电时间等信息
tags: 
- macOS
- 硬盘
categories:
- 技术
---
# 缘起
售卖闲置移动硬盘，买家问及通电时间，我虽不了解，但总能学一学。

# 无效方案：不可用的软件
- 鲁大师：百度看到的第一个答案，无macOS版本
- smart utility for mac: 只能看电脑自带磁盘的信息
- 磁盘工具：系统自带软件，能看到外接磁盘，不显示通电时间信息

# 解决方案：DriveDx
1. 官网下载安装DriveDx，打开DriveDx会显示外接硬盘，但是选中外接硬盘看不到很多信息，此时DriveDx上面会显示建议安装SAT SMART Driver，点击按钮按要求安装好即可（忘了截图但软件标注很明显，下面是官网的旧版截图，没有安装的按钮）

<center>
<img src = "https://p.ipic.vip/cwu74h.JPG" width="65%">
<div style="color:#C0C0C0;font-size:10px;">官网的旧版本</div>
</center>


2. 推出外接磁盘，退出DriveDx
3. 重新打开DriveDx，就能看到外接磁盘的各种信息了

<center>
<img src = "https://p.ipic.vip/8pj2tl.JPG" width="65%">
<div style="color:#C0C0C0;font-size:10px;">DriveDx显示的信息</div>
</center>

注: DriveDx是付费软件，试用期能看到上述信息