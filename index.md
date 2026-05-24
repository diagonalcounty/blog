---
title: Home
---

# Welcome to Diagonal County The Blog

This is my personal writing space. Explore the latest posts below.

## Recent Posts

{% for post in site.posts limit: 5 %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%B %d, %Y" }}
{% endfor %}
