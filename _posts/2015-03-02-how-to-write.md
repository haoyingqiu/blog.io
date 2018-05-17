---
layout: post
title: Python中extend()和append()的区别
date: 2018-5-07
categories: blog
tags: [标签一,标签二]
description: Python中extend()和append()的区别
---

extend()和append()都传一个参数进去

但就效果而言，

extend()相当于传了多个参数进去

append()只传了一个参数

且

extend()只能传列表

append()可以传任意格式的参数

例：

a=[1,2,3,4]

b=[0,9,8]

print（a.extend(b)）

[1,2,3,4,0,9,8]

print（a.append(b)） 

[1,2,3,4,[0,9,8]]












