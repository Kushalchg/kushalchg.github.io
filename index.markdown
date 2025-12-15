---
layout: home
title: Home
---

# Welcome to My Portfolio

Check out my [projects](/projects/) and [materials](/materials/).

## Latest Blogs

{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}
