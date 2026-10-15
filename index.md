---
layout: single
title: "Hongli Ye"
classes: homepage
excerpt: "Mathematics undergraduate at SUSTech, interested in geometric topology, differential geometry, and geometric analysis."
---

<div class="intro-eyebrow">MATHEMATICS · NOTES · LIFE</div>
<h1 class="intro-title">Exploring geometry.<br>Collecting perspectives.</h1>
<p class="intro-lead">Hi, I'm Hongli — a mathematics undergraduate at <a href="https://www.sustech.edu.cn/">SUSTech</a>. Welcome to my corner of the internet.</p>
<p>I am pursuing a B.Sc. in Mathematics, which I began in 2023. My interests lie in geometric topology, differential geometry, and geometric analysis. Here I share what I learn, the notes I write, and a few things beyond mathematics.</p>
<div class="intro-actions"><a class="primary-link" href="{{ '/assets/pdf/Personal_CV_Acadamic.pdf' | relative_url }}">View my CV <span aria-hidden="true">↗</span></a><a href="{{ '/about/' | relative_url }}">More about me <span aria-hidden="true">→</span></a></div>

<div class="interest-strip"><span>Geometric topology</span><span>Differential geometry</span><span>Geometric analysis</span></div>

<section class="home-section" aria-labelledby="notes-heading">
<div class="section-heading"><div><p class="section-kicker">THE MATHEMATICAL NOTEBOOK</p><h2 id="notes-heading">Learning, written down.</h2></div><a href="{{ '/seminar/' | relative_url }}">All seminar notes <span aria-hidden="true">→</span></a></div>
<p class="section-description">Lecture notes and seminar talks, carefully set in LaTeX.</p>
{% for note in site.data.seminars limit:3 %}
<article class="note-row"><div class="note-date">{{ note.date | date: "%b %Y" }}</div><div><h3><a href="{{ note.pdf | relative_url }}">{{ note.title }}</a></h3><p>{{ note.series }}</p></div><a class="pdf-link" href="{{ note.pdf | relative_url }}" aria-label="Download {{ note.title }} PDF">PDF <span aria-hidden="true">↗</span></a></article>
{% endfor %}
<a class="text-link" href="{{ '/courses/' | relative_url }}">Browse course notes <span aria-hidden="true">→</span></a>
</section>

<section class="home-section life-section" aria-labelledby="life-heading">
<div class="life-copy"><p class="section-kicker">AWAY FROM THE BLACKBOARD</p><h2 id="life-heading">Life, in the margins.</h2><p>There is more to life than mathematics. I enjoy volleyball, traveling, and keeping a record of the places I visit.</p><a class="text-link" href="{{ '/blog/' | relative_url }}">Read the journal <span aria-hidden="true">→</span></a></div>
<a class="life-image" href="{{ '/2026/03/15/Days-in-Nice-and-Marseille.md.html' | relative_url }}"><img src="{{ '/assets/photos/2526Win-EUR/Nice1.JPG' | relative_url }}" alt="The Côte d’Azur, photographed during my travels in Nice" loading="lazy"><span>POSTCARDS FROM THE CÔTE D’AZUR <span aria-hidden="true">↗</span></span></a>
</section>
