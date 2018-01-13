[![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/) [![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/ShixiangWang/scripting_course/graphs/commit-activity) [![GitHub issues](https://img.shields.io/github/issues/ShixiangWang/scripting_course.svg)](https://GitHub.com/ShixiangWang/scripting_course/issues/) [![GitHub issues-closed](https://img.shields.io/github/issues-closed/ShixiangWang/scripting_course.svg)](https://GitHub.com/ShixiangWang/scripting_course/issues?q=is%3Aissue+is%3Aclosed) 

原仓库-->[English version](https://github.com/learnbyexample/scripting_course)，有问题上Gitter聊天室，点击[![Join the chat at https://gitter.im/learnbyexample/scripting_course](https://badges.gitter.im/learnbyexample/scripting_course.svg)](https://gitter.im/learnbyexample/scripting_course)。

中文交流Gitter聊天室，点击[![Join the chat at https://gitter.im/Scripts-tyro/Lobby](https://badges.gitter.im/Scripts-tyro/Lobby.svg)](https://gitter.im/Scripts-tyro/Lobby)

**推荐**：[Discord中文聊天室](https://discord.gg/7TNWGn)

# 脚本课程

一个Linux命令行、Vim和脚本的参考指南

* [Linux命令行](https://github.com/ShixiangWang/Linux_command_line) - 介绍Linux命令和Shell脚本
* [命令行文本处理](https://github.com/ShixiangWang/Command-line-text-processing) - 从查找文本到搜索和替换，从排序到美化文本以及更多 
* [Vim 参考](https://github.com/ShixiangWang/vim_reference) - Vim初学者到进阶的参考指南
* [Perl 介绍](https://github.com/ShixiangWang/Perl_intro) - 通过实例演示的Perl5介绍课程
* [Python基础](https://github.com/ShixiangWang/Python_Basics) - 语法，处理Shell命令、文件、文本处理等等...

<br>

## 在虚拟机上尝试Linux

* [安装Linux虚拟机简介](https://jingyan.baidu.com/article/14bd256e0ca52ebb6d26129c.html) （**注**：我个人还是推荐使用[ubuntu系统](https://www.ubuntu.com/download/desktop)，用习惯了，感觉比较好用，当然你也可以按照下方说明操作）
* 至于Linux发行版，你可以使用我（原作者）自定义的 [Porteus](http://build.porteus.org/)，我在其中添加了gvim、Perl、Python2和Python3。它是一个轻量级的发行版（ISO文件 < 200MB），所以选择512MB的内存对于基本的需求就足够了，而且启动在5秒以内
  * Porteus_32bit.iso [原镜像地址](https://drive.google.com/open?id=0B7SzVctdXWlUYy1QZG1NX2xyYVk) [百度云地址](https://pan.baidu.com/s/1o9AqrYM)
  * Porteus_64bit.iso [原镜像地址](https://drive.google.com/open?id=0B7SzVctdXWlUV3kyNlhMU29PMUk) [百度云地址](https://pan.baidu.com/s/1kW7E9aZ)
  * 两个版本都有 `/tmp/useful_files/`目录，包含dot文件（要拷贝到home目录）和一些学习Perl和Python3的程序。
  * root用户的默认密码是`toor`，guest则是`guest` -  [Porteus FAQ](http://www.porteus.org/faq.html)
* 如果你看到**kernel panic**这样的错误，你可能需要 [Enable Intel VT-x in Your Computer’s BIOS or UEFI Firmware](http://www.howtogeek.com/213795/how-to-enable-intel-vt-x-in-your-computers-bios-or-uefi-firmware/)。

选择Linux发行版本、安装和系列应用等等的进一步**阅读指南**

* [awesome-linux](https://github.com/aleksandar-todorovic/awesome-linux#distributions)
* [computefreely](http://computefreely.org/)
* [Arch wiki - list of applications](https://wiki.archlinux.org/index.php/List_of_applications)
* [alternativeto - Crowdsourced software recommendations](http://alternativeto.net/)

<br>

## 整理的资源

免费学习资源和问答论坛列表

* [Linux](./Linux_curated_resources.md)
* [Vim](./Vim_curated_resources.md)
* [Perl](./Perl_curated_resources.md)
* [Python](./Python_curated_resources.md)

整理的编程、书籍、视频、音乐、游戏等等列表

* [Curated Resources](https://github.com/ShixiangWang/curated_resources)

<br>

## dot文件

不要拷贝bash和vim自定义的文件（文件名以.起始）直接到你的home目录。你可能会覆盖当前一些有用的设置。理解它们并在必要时添加。

<br>

## 许可证协议
本工作基于 [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/)

[![licensebuttons by-nc-sa](https://licensebuttons.net/l/by-nc-sa/3.0/88x31.png)](https://creativecommons.org/licenses/by-nc-sa/4.0)
