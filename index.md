---
layout: page
title: やまなかむら たろうの　ぶろぐ
---
{% include JB/setup %}

    
## 記事一覧

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

