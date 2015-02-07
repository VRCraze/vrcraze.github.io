---
layout: page
title: 欧阳的学习笔记
tagline: Supporting tagline
---
    
## 文章集

所有文章

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>