---
layout: page
title:  飞雪无情的博客 
tagline: 专注于Android、Java、移动互联网、项目管理、软件架构
---
{% include JB/setup %}

## 所有文章
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date: "%Y-%m-%d %H:%M:%S" }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
    <br/>
  {% endfor %}
</ul>


