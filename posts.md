---
layout: default
title: Posts
---

# Blog Posts

{% for post in site.posts %}
  - [{{ post.title }}]({{ post.url }})
{% endfor %}
