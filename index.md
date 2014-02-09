---
layout: page
title: jackzou19
tagline: 
---
{% include JB/setup %}

jackzou19 在上海工作的吉安人。jackzou19@163.com 
##我发布的文章列表
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



