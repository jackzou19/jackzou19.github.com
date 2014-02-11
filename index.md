---
layout: page
title: jackzou19
tagline: 
---
{% include JB/setup %}

####这是我用jekyll和github做的博客，用vim写的文章、非常有趣。你也可以试试。

联系我可以mail  jackzou19@163.com ，微博 @jackzou
###文章列表
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



