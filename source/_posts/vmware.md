---
title: vmware
date: 2021-11-24 13:26:30
tags:
---
# 常见问题

##### VMware Tools灰色

[网址](https://www.php.cn/faq/454454.html)

1 、打开虚拟机，依次点击虚拟机、设置

2、点击【添加】，选择“CD/DVD驱动器”，点击【完成】；

3、选择刚才添加的“新CD/DVD驱动器”，勾选"使用IOS映象文件"，点击“浏览”，**找到虚拟机安装目录，找到linux.iso文件并选择**，点击“打开”，最后点击【确定】即可；

完成之后，系统桌面就会显示像光驱一样的圆形“Vmware Tools”图标，双击它就出现你想要的文件了

##### Windows与linux虚拟机共享文件夹教程

##### [网址](https://blog.csdn.net/xiao_bai_9527/article/details/79201150)

1.打开虚拟机界面，并启动linux

2.选中上方功能栏中的虚拟机，选中设置

3.在选项里选择`共享文件夹`，右边选择`总是启用`，添加文件夹路径，确定

4.进入虚拟机 解压

```
tar -xzvf VmwareTools-......
sudo su
sudo ./vmware-install.pl
一路yes
```

在/mnt/hgfs/下查看共享文件



