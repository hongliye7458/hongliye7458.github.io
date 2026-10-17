---
layout: single
title: Hongli Ye
excerpt: Mathematics undergraduate at SUSTech.
---

I am an undergraduate student in Mathematics at the [Southern University of Science and Technology](https://www.sustech.edu.cn/), where I began my B.Sc. in 2023.

My interests include geometric topology, differential geometry, and geometric analysis. Outside mathematics, I enjoy volleyball and traveling.

[GitHub](https://github.com/hongliye7458) · [More about me](/about/)

## Lecture notes

I enjoy writing up my notes in LaTeX. Here are notes from courses I have taken.

<ul class="simple-list">
<li><a href="{{ '/assets/pdf/Topics_in_High_Dimension_Manifold_Topology.pdf' | relative_url }}">Topics in High-dimensional Manifold Topology</a><span class="list-date">Summer 2026 · Sichuan University</span></li>
<li><a href="{{ '/assets/pdf/Introduction_to_Riemannian_Geometry.pdf' | relative_url }}">Riemannian Geometry</a><span class="list-date">Spring 2026 · SUSTech</span></li>
<li><a href="{{ '/assets/pdf/MA215_Probability.pdf' | relative_url }}">Probability</a><span class="list-date">Fall 2024 · SUSTech</span></li>
</ul>

[All course notes](/courses/)

## Blog

Travel experiences, everyday life, and occasional thoughts.

<ul class="simple-list">
{% for post in site.posts limit:3 %}
<li><a href="{{ post.url | relative_url }}">{{ post.title }}</a><span class="list-date">{{ post.date | date: "%b %-d, %Y" }}</span></li>
{% endfor %}
</ul>
