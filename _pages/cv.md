---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education

- **PhD in Computer Science**, University of Wisconsin–Madison, 2024–2029 (expected)
- **B.S. in Computer Science, Honors Mathematics, and Honors Statistics**, University of Michigan–Ann Arbor, 2021–2024

## Experience

- **Research Assistant**, University of Wisconsin–Madison — Summer–Fall 2025
  - Research in optimization and learning theory, advised by Prof. Jelena Diakonikolas.

- **Teaching Assistant**, University of Wisconsin–Madison — Fall 2024, Spring 2025, and 2026
  - CS 220 (Data Science Programming I) and CS 412 (Introduction to Numerical Methods).

- **Software Engineering Intern**, Amazon Web Services — Summer 2023
  - Boston, Massachusetts.

## Publications

<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

## Teaching

<ul>
{% for post in site.teaching reversed %}
  <li><strong><a href="{{ post.url | relative_url }}">{{ post.title }}</a></strong>{% if post.term %}, {{ post.term }}{% endif %}</li>
{% endfor %}
</ul>
