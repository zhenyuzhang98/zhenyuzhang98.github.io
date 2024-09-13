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
* Ph.D. in Theoretical Physics, Peking University, June 2025 (expected)
* B.S. in Physics, Sun Yat-Sen University, June 2020

Research experience
======
* September 2021 - Present: Black hole images
  * Supervisor: [Prof. Bin Chen](https://inspirehep.net/authors/1013901?ui-citation-summary=true)

* August 2023 - Present: Primordial black holes and the early universe
  * Supervisor: [Prof. Shi Pi](https://stonepi.github.io)

* October 2018 - August 2020: Cosmological large-scale structure
  * Supervisor: [Prof. Xiao-dong Li](https://inspirehep.net/authors/1024776?ui-citation-summary=true)

Teaching experience
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Academic Honors
======
* Peking University President Scholarship, June 2024.
* Peking University President Scholarship, June 2023.
* Outstanding Student Presentation Award in the 2022 Annual Conference of Division of Gravitation and Relativistic Astrophysics, Chinese Physical Society, July 2022.
* Sun Yat-Sen University First-Class Scholarship for Undergraduates, September 2018.
* National Scholarship for Undergraduate, September 2017.
 
Programming Skills
======
* Competent in 
  * Wolfram Mathematica
  * Python
  * Linux
* Familiar with 
  * C
* With some basic knowledge of 
  * Julia
  * Fortran

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Selected papers
======
{% if site.author.inspire %}
  <div class="wordwrap">You can find a full list of my papers on <a href="{{site.author.inspire}}">my INSPIRE profile</a>.</div>
{% endif %}
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
 
