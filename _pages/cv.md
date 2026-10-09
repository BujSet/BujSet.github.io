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
* Ph.D. in Computer Science, University of Wisconsin-Madison, August 2026
* M.S. in Computer Science, University of Wisconsin-Madison, May 2022
* M.S. and B.S. in Electrical and Computer Engineering, Carnegie Mellon University, May 2020

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
