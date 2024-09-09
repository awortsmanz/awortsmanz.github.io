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
* Ph.D at the Center for Data Science, École Normale Superieure, 2024-Present (First Year)
* M.S. in Mathematics and Applications, Université Paris-Dauphine 2023-2024
* B.S. in Applied Mathematics, Universidad de Chile 2023

Work experience
======
* Spring 2024: Research Intern
  * Center for Data Science, École Normale Superieure
  * Supervisor: Bruno Loureiro

* Spring 2022: Research Intern
  * INRIA Bordeaux
  * Supervisor: Simone Labarthe and Clémence Frioux
  
Skills
======
* Python
* Spanish, English, French. 

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
  
