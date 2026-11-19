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
* **PhD in Mathematics** (ongoing)
  * Mathematics Münster & University of Stuttgart
* **M.Sc. in Mathematics**, University of Münster
  * Thesis: *Model order reduction using group convolutional autoencoders*
  * Supervisors: Prof. Dr. Mario Ohlberger and Dr. Stephan Rave
{% comment %} TODO: add your B.Sc. (subject, university, year) and years for the degrees above {% endcomment %}

Software
======
* Contributor to [pyMOR](https://pymor.org), Model Order Reduction with Python

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
