---
title: Posts
---


{% for post in site.posts %} - **[{{ post.title }}]({{ post.url }})** — {{ post.date | date: "%B %d, %Y" }} {{ post.excerpt | strip_html | truncatewords: 25 }} {% endfor %}
