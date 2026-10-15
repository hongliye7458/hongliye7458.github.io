---
layout: single
title: Blog
permalink: /blog/
---

<p class="page-intro">Travel stories, everyday moments, and thoughts along the way.</p>

{% for post in site.posts %}
<article class="reading-entry journal-entry">
<p class="entry-meta">{{ post.date | date: "%B %-d, %Y" }}</p>
<h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
<p>{{ post.excerpt | strip_html | truncate: 220 }}</p>
<a class="text-link" href="{{ post.url | relative_url }}">Read story</a>
</article>
{% endfor %}

[Subscribe via RSS](/feed.xml)
