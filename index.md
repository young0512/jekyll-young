---
layout: page
title: Young's Blog
tagline: 进步每一天
---
{% include JB/setup %}

    
### Blog Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

