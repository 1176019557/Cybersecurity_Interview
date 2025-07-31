---
layout: page
title: 资源链接
description: 网络安全学习资源
keywords: 网络安全, 学习资源, 安全社区
comments: true
menu: 资源链接
permalink: /links/
---

## 网络安全学习资源

这里收集了各类优质的网络安全学习资源，帮助你系统学习网络安全知识。

### 安全社区与平台

<ul>
{% for link in site.data.links %}
  {% if link.src == 'security' %}
  <li><a href="{{ link.url }}" target="_blank">{{ link.name}}</a></li>
  {% endif %}
{% endfor %}
</ul>

### 推荐书籍

- 《Web安全深度剖析》
- 《白帽子讲Web安全》
- 《网络安全攻防实战指南》
- 《CTF特训营》
- 《内网安全攻防》
- 《网络安全应急响应技术实战指南》

### 在线学习平台

- [TryHackMe](https://tryhackme.com/)
- [HackTheBox](https://www.hackthebox.eu/)
- [VulnHub](https://www.vulnhub.com/)
- [CTF Time](https://ctftime.org/)
- [Cybrary](https://www.cybrary.it/)
- [SANS Cyber Aces](https://www.cyberaces.org/)

### 更多安全资源

<ul>
{% for link in site.data.links %}
  {% if link.src == 'www' %}
  <li><a href="{{ link.url }}" target="_blank">{{ link.name}}</a></li>
  {% endif %}
{% endfor %}
</ul>
