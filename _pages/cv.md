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
  * Calculated black hole images using the general relativistic ray-tracing (GRRT) method, considering different astronomical environments, various light sources such as accretion disks, hotspots and jets.
  * Investigated black hole shadow and polarization patterns.
  * Explored charged particle dynamics around magnetized black holes.
  * Developed an analytical morphological model of the accretion disk and funnel wall.
  * Investigating the autocorrelation of black hole movies using dynamic light sources in order to extract physical information of the black hole or its accretion disk. (Ongoing project)

* August 2023 - Present: Primordial black holes and the early universe
  * Supervisor: [Prof. Shi Pi](https://stonepi.github.io)
  * Calculating the abundance of PBHs using both the extended Press-Schechter approach and peak theory, and constraining it with future gravitational wave detectors. (Ongoing project)

* October 2018 - August 2020: Cosmological large-scale structure
  * Supervisor: [Prof. Xiao-Dong Li](https://inspirehep.net/authors/1024776?ui-citation-summary=true)
  * Used the tomographic Alcock-Paczynski test with non-parametric statistical methods to reconstruct the dark energy equation of state parameter.
  * Developed a deep learning technique to infer the dark matter nonlinear velocity field from its density field.

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
  * C/C++
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
  
 
