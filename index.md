---
layout: page
title: Codelicious
---
{% include JB/setup %}

My blog is under migration. It's pretty ugly during this time.

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


