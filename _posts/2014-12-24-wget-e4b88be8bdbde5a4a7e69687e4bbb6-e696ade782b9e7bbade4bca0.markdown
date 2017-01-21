---
author: liuadmin
comments: true
date: 2014-12-24 01:43:03+00:00
excerpt: wget 下载大文件-断点续传\r<br />wget -c -b -t 0 -O CentOS-7.0-1406-x86_64-Everything.iso  http://mirrors.sohu.com/centos/7/isos/x86_64/CentOS-7.0-1406-x86_64-Everything.iso
  -o centos.log\r<br />
layout: post
slug: wget-%e4%b8%8b%e8%bd%bd%e5%a4%a7%e6%96%87%e4%bb%b6-%e6%96%ad%e7%82%b9%e7%bb%ad%e4%bc%a0
title: wget 下载大文件-断点续传
wordpress_id: 53329
categories:
- opensource
tags:
- tips
- wget
---

举例如下：

wget -c -b -t 0 -O CentOS-7.0-1406-x86_64-Everything.iso  http://mirrors.sohu.com/centos/7/isos/x86_64/CentOS-7.0-1406-x86_64-Everything.iso -o centos.log

下载一个7GB的DVD文件，能够断点续传，能够把状态写入centos.log文件中。具体参数说明如下：

[su_table]
<table >
<tbody >
<tr >

<td >-c
</td>

<td >断点续传
</td>
</tr>
<tr >

<td >-b
</td>

<td >后台下载
</td>
</tr>
<tr >

<td >-t 0
</td>

<td >反复尝试下载，0（零）为不限次数
</td>
</tr>
<tr >

<td >-O file name
</td>

<td >O（大写字母o）下载的文件命名为
</td>
</tr>
<tr >

<td >-o file name
</td>

<td >o（小写字母o）下载的日志保存在文件中
</td>
</tr>
<tr >

<td >URL
</td>

<td >http://mirrors.sohu.com/centos/7/isos/x86_64/CentOS-7.0-1406-x86_64-Everything.iso
</td>
</tr>
</tbody>
</table>
[/su_table]

本文参考：[http://blog.chinaunix.net/uid-14735472-id-111049.html](http://blog.chinaunix.net/uid-14735472-id-111049.html)
