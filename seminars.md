---
layout: single
title: Seminar notes
permalink: /seminar/
---

<p class="page-intro">Talks, ideas, and notes from mathematics seminars.</p>

{% for note in site.data.seminars %}
<article class="reading-entry">
<p class="entry-meta">{{ note.date | date: "%B %-d, %Y" }}</p>
<h2><a href="{{ note.pdf | relative_url }}">{{ note.title }}</a></h2>
<p class="entry-series">{% if note.series_url %}<a href="{{ note.series_url }}">{{ note.series }}</a>{% else %}{{ note.series }}{% endif %}<br>Organized by <a href="{{ note.host_url }}">{{ note.host }}</a></p>
{% if note.description %}<p>{{ note.description }}</p>{% endif %}
<a class="text-link" href="{{ note.pdf | relative_url }}">Read notes <span class="file-tag">PDF</span> <span aria-hidden="true">↗</span></a>
</article>
{% endfor %}
