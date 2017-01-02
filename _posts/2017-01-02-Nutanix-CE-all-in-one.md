---
layout:     post
title:      Nutanix CE All In One
summary:   Nutanix CE是Nutanix社区版软件的简称，它是Nutanix企业版产品的功能精简集合，是体验和测试Nutanix技术的很方便的途径。
categories: Nutanix
---

## Nutanix Community Edition 社区版简介
![Community_Edition_-_Nutanix](/images/Community_Edition_-_Nutanix.png)

这个产品目前的位置在 [https://www.nutanix.com/products/community-edition/](https://www.nutanix.com/products/community-edition/)；目前这个页面还没有中文化，下面简单介绍以下。

* Feature Rich Software  它是一个功能丰富的软件
* Broad Hardware Support & Available On-demand 很丰富的硬件支持，在网上可以按需体验
* Zero Cost 零成本

用Nutanix CE社区版体验，体验超融合技术的三个步骤。

1. 注册 ： 这次Nutanix社区，下载安装镜像
2. 部署 ： 在你的服务器上部署，或者在Ravello上在线开启体验；[官方安装部署视频点这里](https://www.youtube.com/watch?v=xKtQRp6dcAc)
3. 玩耍 ： 安装完之后就可以开心地玩耍了，有问题请移步 [社区版论坛](http://next.nutanix.com/t5/Discussion-Forum/bd-p/Discussion)

用物理机安装和体验的几点注意事项如下：

* 物理机安装支持1，3，4个节点的部署；推荐内存在32GB以上；由于版本CE 2016.12.22的CVM的内存需求是24GB，由于加入了自服务门户功能；建议使用SSD硬盘，最好能混搭一些普通硬盘。
* 安装后的首次启动需要系统能链接互联网，否则CVM会启动不了，首次启动成功之后就不用再联网了
* 用虚拟机安装，请注意本机的内存，和给虚拟机分配的内存，网上也有修改对内存和CPU限制修改的脚本

产品在社区里的文档页面： [点这里](http://next.nutanix.com/t5/Discussion-Forum/Download-Nutanix-CE-Docs-and-Guides/m-p/16442#U16442)

## 参考配置
Intel NUC 最新版一台，i7处理器，两条16GB内存，两条512GB硬盘。它的好处是便携；然而内存还是有限，不能跑多少个虚拟机。

## 相关文档

* [在VMware Workstation上安装Nutanix CE](http://huanwenli.blog.51cto.com/2848240/1749083)
* [Nutanix Community Edition安装在vSphere环境中](http://www.nextech.space/nextech/2016/06/nutanix-community-edition%E5%AE%89%E8%A3%85%E5%9C%A8vsphere%E7%8E%AF%E5%A2%83%E4%B8%AD/)
* [http://nutanix.club/](http://nutanix.club/)
* [Nutanix圣经](http://nutanixbible.com/)

