---
layout: page
title: "Blog"
---

## Blog
Welcome to my blog where I share insights on Machine Learning, AI, and career growth.

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}
