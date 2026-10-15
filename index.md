---
layout: single
title: Hongli Ye
excerpt: Mathematics undergraduate at SUSTech.
---

I am an undergraduate student in Mathematics at the [Southern University of Science and Technology](https://www.sustech.edu.cn/), where I began my B.Sc. in 2023.

My interests include geometric topology, differential geometry, and geometric analysis. Outside mathematics, I enjoy volleyball and traveling.

[CV](/assets/pdf/Personal_CV_Acadamic.pdf) · [GitHub](https://github.com/hongliye7458) · [More about me](/about/)

## Notes

I enjoy writing up my notes in LaTeX. You can find my [course notes](/courses/) and [seminar notes](/seminar/) here.

Recent seminar notes:

<ul class="simple-list">
{% for note in site.data.seminars limit:3 %}
<li><a href="{{ note.pdf | relative_url }}">{{ note.title }}</a><span class="list-date">{{ note.date | date: "%b %-d, %Y" }}</span></li>
{% endfor %}
</ul>

## Blog

Travel experiences, everyday life, and occasional thoughts.

<ul class="simple-list">
{% for post in site.posts limit:3 %}
<li><a href="{{ post.url | relative_url }}">{{ post.title }}</a><span class="list-date">{{ post.date | date: "%b %-d, %Y" }}</span></li>
{% endfor %}
</ul>
