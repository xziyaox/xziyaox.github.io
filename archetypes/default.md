---
title: "{{ replace .Name "-" " " | title }}" #标题
date: {{ .Date }} #创建时间
lastmod: {{ .Date }} #更新时间
author: ["子耀"] #作者
categories:
tags:
description: "" #描述
weight: # 输入1可以顶置文章，用来给文章展示排序，不填就默认按时间排序
url:
draft: false # 是否为草稿
comments: false #是否展示评论
showToc: true # 显示目录
TocOpen: false # 自动展开目录
hidemeta: false # 是否隐藏文章的元信息，如发布日期、作者等
disableShare: true # 底部不显示分享栏
showbreadcrumbs: true #顶部显示当前路径
---
