# 给 Windows 技术同事的 Linux 入门指南(讲义)
* Author: Liangdi(wu@liangdi.me)
* Last Updated (2017-07-16)

#### 为啥会有这份文档？

> 公司技术同事目前大部分还是使用 Windows 作为开发系统，而在公司的技术栈中大量使用 Linux 相关的东西，或者是从 Linux 开始发展起来的东西，如 git/git bash，同时，公司的业务系统基本都是部署在 CentOS (一个 Linux 发行版) 中，所以所有技术人员有必要对 Linux 有个基础的了解和认识。

* ### 避免圣战
  * Windows vs Linux vs MacOS
  * Chrome vs Firefox
  * Vim vs Emacs
  * PHP vs Java vs C# vs ...
  * Tab vs Space
  * ...
  * ...

* ### Linux 介绍与现状
  * Linus 1991 年第一次发布 Linux 0.01
  * Linux 的一些设计思想
    * kiss
    * 一切兼文件
    * 约定 (大家按照一定标准做事情)
    * 提供机制而不是策略 (面向对象中的‘针对接口编程，而不是针对实现编程’)
  * 众多的发行版
    * RHEL
    * CentOS
    * Debain
    * Ubuntu
    * Fedora
    * Deepin


* ### shell 基本知识
  * 内核和 shell
  * bash/命令行/脚本?
  * man
  * vim 如何退出

* ### 软件管理
  * 不是安装什么软件都是 ./configure && make && make install (编译安装)
  * 软件包管理机制 (安装软件 so easy)
  * APT
  * yum / dnf
* ### 用户系统
  * root
  * 普通用户
  * home 目录
  * sudo / su
* ### 文件系统
  * 物理分区
  * Windows 中的 C/D/E/F... 盘和 Linux 中的根目录(/)
  * / 和 \ 不同的文件分隔
* ### 服务管理
  * System V init/Upstart/systemd
  * CentOS 7.x 中的 systemd
  * Windows 中的 Net start/stop 与 sc
* ### 体验 Linux
  * Ubuntu On Windows 10
  * 内网提供 CentOS 7.x 的虚拟机
