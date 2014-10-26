
PXEBoot 简易安卓 PXE 启动服务器

## 功能介绍

  PXEBoot 是一个轻量级的TFTP，FTP，HTTP，和proxyDHCP，主要利用手机的WIFI网络提供一个基础的PXE启动服务。
同一个网络下的电脑可以通过PXE服务来启动引导一些维护工具，甚至是基于网络的操作系统。

  本应用需要 Root 权限，否则无法正常工作。

  默认提供三个启动选项菜单，用户可以选择自己喜欢的菜单进入。


  软件界面截图

  ![](http://b.chenall.net/main.png)

  可以选择性开启TFTP/HTTP/FTP服务（这些服务都使用相同的根目录）。

  使用iPXE菜单进入后的默认界面
  
  ![](http://b.chenall.net/ipxe.png)

  使用grub4dos菜单的默认界面
   
  ![](http://b.chenall.net/grub4dos.png)


  
## 其它说明

  部份设备可能不兼容本应用。
  如果没有出现ipxe/grub4dos/pxelinux的启动菜单界面，可以尝试禁用proxyDHCP功能。
  如果出现了三个启动菜单，但是所有的菜单都无法启动，显示tftp time out可以尝试更换tftp服务。

  本应用是开源的： https://github.com/chenall/Android-PXEBoot  

  可以到这里报告BUG: https://github.com/chenall/Android-PXEBoot/issues

  最新版下载地址：http://b.chenall.net/PXEBoot.apk