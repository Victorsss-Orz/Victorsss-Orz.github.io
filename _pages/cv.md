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

- M.S. in Computer Science, University of Illinois Urbana-Champaign, 2025 (expected)
  - Advisor: Mariana Silva
  - Research Interest: Computer Science Education
- B.S. in Mathematics & Computer Science, University of Illinois Urbana-Champaign, 2023

# Work experience

- Fall 2024: Software Developer
  - PrairieLearn, Inc.
  - Implement LLM-based grading interface in PrairieLearn core, including access control and billing
  - Implement LLM grading accuracy statistics in PrairieLearn core, including access control

# Skills

- Programming
  - Python, Javascript/Typescript, PostgreSQL/mySQL, Docker, Github, C/C++

# Publications

  <ul>{% for post in site.publications reversed %}
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
