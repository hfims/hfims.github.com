---
layout: post
title: "成功让干扰GDIFY网速的家伙下地狱了！"
date: 2012-11-05 13:29
comments: true
category: misc
---

感谢Dan和Steve的提醒，我查了下ARP，果然有人使用P2P终结者等软件。经过WireShark抓包，
获得其MAC地址：f0:4d:a2:fb:81:c4 。 然后用Linux（神器！）的pktgen把它轰炸下了地狱!
网速立即恢复。现给出正确网管地址与IP：

IP 192.168.2.1

MAC 3c:e5:a6:01:7b:3f
