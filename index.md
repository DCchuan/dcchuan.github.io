---
layout: default
title: "首页"
---

# 欢迎来到我的博客！

这里是我的个人博客，记录着我对技术的理解、学习的心路历程以及生活的点点滴滴。

> “分享使我成长” — 这是我的座右铭。

## 最新文章

{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
