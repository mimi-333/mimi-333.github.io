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

* B.E. in Intelligent Systems Engineering — Hiroshima City University, 2023  
* M.E. in Intelligent Systems Engineering — Hiroshima City University, 2025  
* Ph.D. Program (1st year) — Graduate School of Information Sciences, Hiroshima City University

Programming Skills
======
* Python
* C++

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
  
Certifications
======
* Passed Fundamental Information Technology Engineer Examination
* Passed Applied Information Technology Engineer Examination
