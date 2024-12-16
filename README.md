# Asynchronous Programming with C++
*1st Edition*

*通过多线程和异步编程打造高速运行的软件*<a href=""><img src="cover.png" height="256px" align="right"></a>

* 作者：Javier Reguera-Salgado / Juan Antonio Rufes
* 译者：陈晓伟
* Packt Publishing Ltd. (出版于: 2024年11月29日)

> [!IMPORTANT]
> 翻译是译者用自己的思想，换一种语言，对原作者想法的重新阐释。鉴于我的学识所限，误解和错译在所难免。如果你能买到本书的原版，且有能力阅读英文，请直接去读原文。因为与之相较，我的译文可能根本不值得一读。
>
> — 云风，程序员修炼之道第2版译者

## 本书概述

随着硬件技术的不断进步，带来了更大的内存容量和更多的CPU核心，软件必须进化以高效利用所有可用资源并减少闲置的CPU周期。在本书中，两位拥有合计约五十年经验的资深软件工程师将教你如何在C++中实现并发和异步解决方案。

你将获得对并行编程范式的全面理解——涵盖并发、异步、并行、多线程、反应式和事件驱动编程，以及数据流——并了解线程、进程和服务之间的关系。深入到并发的核心部分，作者会指导你创建和管理线程，并探索C++中的线程安全机制，包括互斥锁、原子操作、信号量、条件变量、门闩和屏障。有了这个坚实的基础，你会专注于纯粹的异步编程，使用future、promise、async函数和协程。书中逐步引导你使用Boost.Asio和Boost.Cobalt开发网络和低级I/O解决方案，证明性能优化技巧，并测试和调试异步软件。

读完这本关于C++的书后，你将能够使用现代异步C++技术实现高性能软件


## 重点内容

* 学习如何使用现代C++特性，包括future、promise、async和协程来构建异步解决方案

* 使用Boost.Asio开发跨平台的网络和低级I/O项目
* 通过理解软件如何适应机器硬件来掌握优化技巧
* 购买印刷版或Kindle版图书即包含免费的PDF电子书

## 作者简介

**Javier Reguera-Salgado** 是一位拥有超过19年经验的资深软件工程师，专精于高性能计算、实时数据处理和通信协议。他熟练掌握 C++、Python 以及多种其他编程语言和技术，工作范围涵盖低延迟分布式系统、移动应用程序、网络解决方案和企业产品。他在西班牙和英国的研究中心、初创公司、蓝筹公司和量化投资公司都做出过贡献。Javier 以优异的成绩从西班牙维戈大学获得高性能计算博士学位。

**Juan Antonio Rufes** 是一位拥有30年经验的软件工程师，专精于低级和系统编程，主要使用 C、C++、0x86 汇编语言和 Python。他的专业领域包括 Windows 和 Linux 的优化、用于防病毒和加密的 Windows 内核驱动程序、TCP/IP 协议分析，以及如智能订单路由和基于 FPGA 的交易系统等低延迟金融系统。他曾与软件公司、投资银行和对冲基金合作。Juan 毕业于西班牙瓦伦西亚理工大学，获得电子工程硕士学位。



## 本书相关

* github翻译地址：https://github.com/xiaoweiChen/Asynchronous-Programming-with-Cpp

* 译文的LaTeX 环境配置：https://www.cnblogs.com/1625--H/p/11524968.html

  * 禁用拼写检查：https://blog.csdn.net/weixin_39278265/article/details/87931348

  * 使用xelatex编译时需要添加`-shell-escape`和`-8bit`选项，例如：

    `xelatex -synctex=1 -interaction=nonstopmode -shell-escape -8bit "book".tex`

  * 为了内容中表格和目录索引能正常生成，至少需要连续编译两次

  * Latex中的中文字体([思源宋体](https://github.com/notofonts/noto-cjk/releases))和英文字体([Hack](https://github.com/source-foundry/Hack-windows-installer/releases/tag/v1.6.0))，需要安装后自行配置。如何配置请参考主book/css.tex顶部关于字体的信息。

* vscode中配置LaTeX：https://blog.csdn.net/Ruins_LEE/article/details/123555016

