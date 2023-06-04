---
title:  "Flash 档案馆的由来"
categories: blog
permalink: flash-archives.html
tags: [blog]
hide_sidebar: true
summary: "Flash 曾经是互联网的一部分，也为互联网带来了繁荣。Flash 的落幕代表着一个时代的结束，它承载着我们许多的回忆。Flash 档案馆目前收录了 8000 多个历史上热门的各类 Falsh 动画，通过 Ruffle 技术进行渲染播放，无需安装插件。"
---

Flash 档案馆存档了大概有 8000 多个动画，都是 2010 年之前的。这个存档里面没有游戏，只有纯动画，里面包含了当时比较有名的蜗牛仔仔（思妙）、大闹西游（思妙）、大话三国（Showgood）、小小系列、流氓兔系列、阿贵系列、小破孩系列等等。

为了方便海外的研究者使用，加入了作品的英文名称，不过是谷歌机翻的，不一定准。这个存档除了支持 Flash Player 插件播放，也支持使用 WebAssembly 的 [Ruffle](https://ruffle.rs/) 播放。

Ruffle 是一个用 Rust 编写的 Flash Player 模拟器。Ruffle 在所有现代操作中原生运行系统作为一个独立的应用程序，并通过使用 WebAssembly 在所有现代浏览器上。利用现代浏览器沙箱的安全性和 Rust 的内存安全保证，我们可以自信地避免 Flash 闻名的所有安全陷阱。Ruffle 将 Flash 放回了它所属的网络上 - 包括iOS和Android上的浏览器！

{{site.data.alerts.tip}}
<p>进入 <b><a href='{{ "/flash-archive/" | prepend: site.computer_museum_base_url }}' target='_blank'>Flash 档案馆</a></b></p>
<p>Flash 档案馆未对手机端进行优化，建议使用电脑浏览器访问。</p>
{{site.data.alerts.end}}

Flash 曾经是互联网的一部分，也为互联网带来了繁荣。如今 Flash 的落幕代表着一个时代的结束，它承载着我们许多的回忆。

---------

{% include links.html %}
