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
* Ph.D in Computer Science, University of Wisconsin - Madison, 2024.8 - 2029.5 (expected)
* B.S. in Computer Science, Honors Mathematics and Honors Statistics, University of Michigan - Ann Arbor, 2021.8 - 2024.5

Work experience
======
* Summer 2025, Fall 2025: Research Assistant
  * University of Wisconsin - Madison, Madison, WI
  * Duties includes: Do & Learn how to do research with my supervisor on Optimization and Leanring Theory
  * Supervisor: Prof. Jelena Diakonikolas

* Fall 2024, Spring 2025, 2026: Teaching Assistant
  * University of Wisconsin - Madison, Madison, WI
  * Duties included: Teaching CS 412 & CS 220, basic courses on Numerical Methods & MATLAB/Python Programming

* Summer 2023: Software Engineering Intern
  * Amazon Web Service (AWS), Boston, MA
  * Manager: Patrick Kenney

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
