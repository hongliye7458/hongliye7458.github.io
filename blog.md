---
layout: single
title: Journal
permalink: /blog/
---

<p class="page-intro">Travel stories, everyday moments, and thoughts along the way.</p>

{% for post in site.posts %}
<article class="reading-entry journal-entry">
<p class="entry-meta">{{ post.date | date: "%B %-d, %Y" }}</p>
<h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
{% if post.header.teaser %}<a href="{{ post.url | relative_url }}"><img class="journal-teaser" src="{{ post.header.teaser | relative_url }}" alt="The Côte d’Azur in Nice" loading="lazy"></a>{% endif %}
<p>{{ post.excerpt | strip_html | truncate: 220 }}</p>
<a class="text-link" href="{{ post.url | relative_url }}">Read story <span aria-hidden="true">→</span></a>
</article>
{% endfor %}

[Subscribe via RSS](/feed.xml)
