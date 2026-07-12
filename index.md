---
layout: page
title: Diagonal County
permalink: /
---

Thoughts on history, ideas, and life.

{% for post in site.posts %}
---

### [{{ post.title }}]({{ post.url }})

**{{ post.date | date: "%B %-d, %Y" }}**

{% if post.excerpt %}{{ post.excerpt | strip_html | strip }}{% endif %}

{% endfor %}
