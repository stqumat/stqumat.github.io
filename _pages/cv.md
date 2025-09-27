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
------
* Ph.D., Stony Brook University, 2020 (advisor: Jason Starr)
* B.Sc., University of Science and Technology of China, 2014

Work experience
------
* Nov/2023-current:
  * Research Assistant Professor
  * Institute of Geometry and Physics, Universit of Science and Technology of China

* Oct/2020-Oct/2023: 
  * Postdoc (mentor: Caucher Birkar)
  * Yau Mathematical Sciences Center, Tsinghua University

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
