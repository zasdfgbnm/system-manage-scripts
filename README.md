我自己用的系统管理用的脚本
=========================

系统用的是Gentoo Linux

内核管理脚本
---------------

脚本名称：kernel

该脚本适用于系统中只打算安装一个内核的用户（可以同时安装有有多个内核源码）。

### 使用方法

更改内核配置： kernel config

重新编译内核： kernel rebuild

如果使用了第三方模块，需要修改kernel文件把编译第三方模块的代码加到rebuild_post中


chroot前挂载脚本
------------------

脚本名称：mount-chroot


本地overlay管理脚本
------------------

脚本名称： localoverlay

### 使用方法

使用localoverlay help获取帮助


hosts管理脚本
-------------

脚本名称：hosts

### 使用方法

更新hosts： hosts update
