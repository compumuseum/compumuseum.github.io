---
title:  "电脑博物馆：在活电脑博物馆重建并连接Xerox Alto"
categories: history
permalink: xerox_alto_is_rebuilt_and_reconnected_by_the_living_computer_museum.html
tags: [computer, history]
hide_sidebar: true
summary: "活电脑博物馆修复的Alto电脑将向大众提供一个难得的机会，去亲身体验Alto电脑的魅力，并且我们希望让更多的人有机会体验Alto电脑。"
---

***——这是一个关于技术突破，并能带来更多启发的故事***

大概35年之前，在Xeron PARC的办公室里观看Xerox新款的研究电脑Alto时的情形仍然令我印象深刻，“天啊”我想，“这将是翻天覆地的变革”。

这一切成为现实，Alto许多创新的特点和功能都被微软吸收进Windows和之后的许多软件产品中——并推动这些特性被广泛的使用在个人电脑中。比如说Alto的几项最广为人知的创举：

- 使用鼠标作为指针设备的图形用户界面（GUI）
- 称作Bravo的“所见即所得”的字处理程序，可以称得上是Word的前身
- 黑底白字的显示器以及位图图像
- 面向对象编程
- 基于以太网连接的文件和打印机共享

<div align="center">
    <a href="../images/dnbwg/xerox_alto_is_rebuilt_and_reconnected_by_the_living_computer_museum_01.jpg">
        <img src="../images/dnbwg/xerox_alto_is_rebuilt_and_reconnected_by_the_living_computer_museum_01.jpg"/>
    </a>
    <p><b>修复后的Xerox Alto电脑，展示于活电脑博物馆，运行的游戏是《迷宫战争（Maze War）》</b></p>
</div>

{{site.data.alerts.tip}}
使用SALTO的模拟器，体验 <b><a href='{{ "/player.html?machine=salto" | prepend: site.computer_museum_base_url }}' target='_blank'>Xerox Alto 电脑</a></b>
{{site.data.alerts.end}}

其实Alto电脑本身并没有得到大量的用户，Xerox没有认识到它的巨大潜力，仅仅生产了一小批Alto电脑供给Xerox内部机构、以及一部分政府部门和大学。但是这台电脑很快启发了一些人，比如说我，比尔·盖茨，史蒂·夫乔布斯以及其他软硬件开发者，去设计基于GUI的电脑应用体验，并因此使数百万用户更好的使用电脑的强大功能。

出于对Alto的历史影响的理解，我在活电脑博物馆（The Living Computer Museum）的团队将难得的两台Alto电脑恢复到完全工作的状态。并且由于以太网正是Alto所启用的新功能之一。活电脑博物馆团队开发了3-Mbit网桥使Alto可以和现代PC通信，据我所知，这是自Alto诞生以来第一次可以与现代PC通信。

<div align="center">
    <a href="../images/dnbwg/xerox_alto_is_rebuilt_and_reconnected_by_the_living_computer_museum_02.jpg">
        <img src="../images/dnbwg/xerox_alto_is_rebuilt_and_reconnected_by_the_living_computer_museum_02.jpg"/>
    </a>
    <p><b>3-Mbit以太网收发器内部照片，展示了使用同轴电缆连接Alto的接口</b></p>
</div>

我的团队并非是唯一一个试图保存Alto遗产的团队。在复原Alto的过程中，我们从其他团队的修复经验中学到了许多东西。这其中就包括[Ken Shirriff开始为Y Combinator修复的一台Alto](http://www.righto.com/2016/06/y-combinators-xerox-alto-restoring.html)。考虑到这一点，我们决定公开一个Internet PUP网关，使全世界的Alto网络可以互联互通，这将激发起更多爱好者对这些古老设备的兴趣，并可能启动更多的修复工作。

与此同时，活电脑博物馆修复的Alto电脑将向大众提供一个难得的机会，去亲身体验Alto电脑的魅力，并且我们希望让更多的人有机会体验Alto电脑。这促使我们开发了一款完整的Alto模拟器。

<div align="center">
    <a href="../images/dnbwg/xerox_alto_is_rebuilt_and_reconnected_by_the_living_computer_museum_03.jpg">
        <img src="../images/dnbwg/xerox_alto_is_rebuilt_and_reconnected_by_the_living_computer_museum_03.jpg"/>
    </a>
    <p><b>运行在活电脑博物馆中的ContrAlto模拟器</b></p>
</div>

这款名叫ContrAlto的软件模拟器可以模拟Alto原有的硬件，让Alto软件能够原封不动的运行在现代PC上。ContrAlto采用的是微码级别的模拟技术，可以相当精确的还原Alto电脑的硬件，包括原有的以太网络都被完整复原，因此不同电脑上的Alto模拟器——当然也包括真实的Alto硬件——互相之间可以共享文件，发送电子邮件，并且可以运行古老的Alto游戏。我曾有机会同时操作复原后的Alto电脑和模拟器，这种体验让我回忆起这台包含了无数技术突破电脑，是如何让我看到未来，并将种种可能性付诸实践的。

<div align="center">
    <a href="../images/dnbwg/xerox_alto_is_rebuilt_and_reconnected_by_the_living_computer_museum_04.gif">
        <img src="../images/dnbwg/xerox_alto_is_rebuilt_and_reconnected_by_the_living_computer_museum_04.gif"/>
    </a>
    <p><b>活电脑博物馆的开发团队正在测试使用ContrAlto运行《迷宫战争》游戏</b></p>
</div>

由于Alto电脑为整个行业带来的技术突破以及对我职业生涯的深远影响，重新审视并恢复这些具有历史意义的电脑令我感到其乐无穷，我其它人也能够像我一项享受其中的乐趣，并充满热情的去创造一个更加美好的未来。

ContrAlto下载：[ContrAlto : A Xerox Alto Emulator](https://www.livingcomputermuseum.org/Online-Systems/Press.aspx)

---------

出处：https://zhuanlan.zhihu.com/p/22506565

原文链接：https://medium.com/vulcan-inc/xerox-alto-is-rebuilt-and-reconnected-by-the-living-computer-museum-e56a7e86be91

{% include links.html %}
