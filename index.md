---
layout: default
title: 我的个人博客
---

# 欢迎来到我的博客！

嗨，欢迎来到我的博客！

## 导航
- [首页](#)
- [关于我](about.html)
- [所有帖子]({{ site.baseurl }}/posts)

## 最新帖子
{% for post in site.posts limit:3 %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}

## 联系我
- 邮箱：daccuan@gmail.com
- GitHub：[我的 GitHub 链接](https://github.com/DCchuan)

<style>
    .post-list {
        list-style-type: none;
        padding: 0;
    }
    .post-list li {
        margin: 10px 0;
    }
</style>