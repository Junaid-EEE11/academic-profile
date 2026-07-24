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

* Professional Master's in Applied Statistics and Data Science — Jahangirnagar University

Work experience
======

* Electrical Engineer — Dhaka Power Distribution Company Ltd. (DPDC)
  * Power-distribution systems and substation operation and maintenance

Research interests
======

* Machine learning for energy systems
* Predictive maintenance
* Time-series forecasting
* Smart-grid analytics
* Sustainable energy optimization

Technical focus
======

* Python, pandas, NumPy, scikit-learn
* Statistical analysis and data visualization
* Electrical power systems and distribution-grid operations

Publications
======

<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

Talks
======

<ul>{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html %}
{% endfor %}</ul>

Teaching
======

<ul>{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
