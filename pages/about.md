---
layout: page
title: About
description: 技术改变生活
keywords: Zheng Hao
comments: true
menu: 关于
permalink: /about/
---

一名普通的打字员。
熟悉 Java, python, Angular, TypeScript等的拼写。
能读 C/C++.
读过JDK, JVM, Spring Security, Spring Core部分章节。
想跟风学习一下Deep Learning。

## 联系

{% for website in site.data.social %}
* {{ website.sitename }}：[@{{ website.name }}]({{ website.url }})
{% endfor %}

## Skill Keywords

{% for category in site.data.skills %}
### {{ category.name }}
<div class="btn-inline">
{% for keyword in category.keywords %}
<button class="btn btn-outline" type="button">{{ keyword }}</button>
{% endfor %}
</div>
{% endfor %}
