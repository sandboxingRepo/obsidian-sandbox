---
title: test
date: 2025-03-06T18:42:12+08:00
lastmod: 2025-03-07T09:28:04+08:00
tags:
  - VPS安全
  - 防火墙
blog: "true"
dir: posts
---

‌‌‌‌这几天我的 VPS 接连出现来自欧洲 IP 的访问，目标直指 SSH 端口。虽说安全措施已经加固，但是看着日志心烦，直接用 ufw 给封了。我在网络上搜寻有没有现成的恶意 ip 列表，偶然发现两份由国内高校提供的 IP 黑名单清单，我直接在我的 VPS 上用上了。  

‌‌‌‌IP 地址黑名单一个是 [中科大](https://blackip.ustc.edu.cn/intro.php) 提供的，另一个由 [东北大学](http://antivirus.neu.edu.cn/scan/) 提供。