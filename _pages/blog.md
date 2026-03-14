---
layout: home
title: Blog
permalink: /blog/
---

Here are some of my blog posts.

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})  
  {{ post.date | date: "%B %d, %Y" }}
{% endfor %}
