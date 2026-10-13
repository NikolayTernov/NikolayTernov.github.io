---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* PhD in Political Science, L.N. Gumilyov Eurasian National University, 2021–2025

Work experience
======
* 2024–present: Associate Professor of Sociology and Political Science
  * L.N. Gumilyov Eurasian National University (ENU), Astana, Kazakhstan
  * Teaching and research in sociology and political science, with a focus on computational social science, digital media, political communication, and post-Soviet/Central Asian studies

Skills
======
* Computational methods
  * NLP / embeddings
  * Spatial econometrics
  * Survival analysis
  * Interrupted time-series analysis
  * Web scraping

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
