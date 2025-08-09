---
layout: single
title: "Blog"
permalink: /blog/
author_profile: true
---

## Blog

Here you'll find my thoughts on machine learning, AI trends, and career growth.

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}
