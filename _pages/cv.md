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
* B.A. in Physics, Pomona College, 2025
  * 3.9 GPA, physics major, math minor

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Research
======
* Pomona College Physics Dept, 2024
  * Analyzed cosmological simulations, used machine learning algorithms to identify and investigate stellar stream properties around low-mass galaxies in FIREbox.

* Harvey Mudd College Physics Dept, 2023
  * Modeled exoplanet migration driven by atmospheric loss, then verified our results against simulations in python.  Consulted experts and published a paper summarizing our findings. 

* Portland State University Physics Dept, 2022  
  * Used Google’s MediaPipe AI to develop accessible real-time skeleton tracking and center-of-mass calculation for physics pedagogy. 
  
Experience
======
* Teaching Assistant, Introductory Astronomy, 2024
* Teaching Assistant, Electronics Lab, 2024
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Programming
======
* Python
* JavaScript
* Kotlin
* GLSL
* IDL
* Unix

Languages
======
* English (Native)
* German (B1)
* Spanish (A2)