---
layout: default
title: Ryan's Finance Blog
description: It's an investing blog
---

# Ryan's Finance Blog

Welcome to my investing blog, focused on building passive income through dividend growth investing.

## Posts

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%B %-d, %Y" }}
{% endfor %}
