---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

# Education

- PhD in Computer Science, University of Illinois Urbana-Champaign, 2029/2030
  - Advisor: Mariana Silva
  - Research Interest: Computers and Education
- M.S. in Computer Science, University of Illinois Urbana-Champaign, 2025
  - Advisor: Mariana Silva
  - Research Interest: Computers and Education
- B.S. in Mathematics & Computer Science, University of Illinois Urbana-Champaign, 2023

# Work experience

- Aug 2024 - Dec 2024: PrairieLearn, Inc.
  - Software developer
  - Implement LLM-based grading interface in PrairieLearn core, including access control and billing
  - Implement LLM grading accuracy statistics in PrairieLearn core, including access control

# Skills

- Programming
  - Python, Javascript/Typescript, PostgreSQL/mySQL, Docker, Github, C/C++

# Publications

  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

# Projects

  <ul>{% for post in site.projects %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!-- Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul> -->
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!-- Service and leadership
======
* Currently signed in to 43 different slack teams -->
