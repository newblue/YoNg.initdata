---
date: "2013-12-07"
layout: post
title: 关于YoNg
permalink: '/first/'
categories:
- YoNg
tags:
- YoNg
- neYoNg
---
欢迎使用`YoNg`
=============

*YoNg* 是一个用来将自己的博客编译变成静态网站的工具，灵感来自 *Jekyll* 、 *Ruhoh* 、 *Gor*
之前用过 *Gor* 非常喜欢，编译速度很快，但是有些遗憾啊，代码很混乱， *Gor* 可以看到全部的
源代码，刚开始从 *Gor* 分支出来做修改了一下，最后还是不得不重新写下 *YoNg* ，全部从头开始
写，修改根本改变不了什么，不如重新写一个出来更舒服一点，不管改写还是重新，你都会面对
抓虫子的问题。

代码经过重新编写，实现的功能基本跟 *Gor* 一样，速度、效率基本差别不大。就是可能有虫子还没
有抓出来。

本文位于 `posts/first.md` , 你可以任意处理这个文件。

文件开头是当前文章的元数据

1. `date` 为自动生成, 当然,你可以修改,这是你的自由
2. `permalink` 可以是固定地址,也可以由`YoNg`为你自动生成
3. `categories` 就是分类, 可以多个
4. `tags` 同理,多个标签也是很常见的

请确保文件使用UTF8（不含BOM）编码

你可以通过执行下面的语句来新建一篇博客:
=======================================

    yong post "文章标题"

    yong post -image=<图片路径> "文章标题"

编译和预览博客
==============

编译你的博客

	yong compile

预览，可以通过以下命令

	yong http

然后打开你的浏览器,访问 http://127.0.0.1:8080 来预览

使用Markdown来编写博客
======================

[Markdown 语法中文版](http://wowubuntu.com/markdown/) 能让你快速入门其语法

相信[MarkdownPad](http://markdownpad.com)或[liteide](http://code.google.com/p/liteide/)会是你的编写博客的好帮手

如果你打算部署到`Github`的`Pages`上

1. 申请`Github`帐户
2. 新建一个库 `username.github.com` 即你的用户名命名的地址
3. 将`compiled`目录,作为根路径,提交上去`github.com`上
4. 稍等几分钟, 你即可通过 http://username.github.com 访问到

最后
====

祝你使用愉快

如果你有什么看不明白的地方，请自行Google吧，实在找不到答案的话请提交ISSUS。
