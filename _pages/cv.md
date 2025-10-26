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
* Ph.D in Marine Biogeochemistry, University of Gothenburg, 2021-2025
* MPhil. in Science, University of Hong Kong , 2018-2020
* B.S. in Environmental Science, University of Hong Kong, 2013-2017

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
