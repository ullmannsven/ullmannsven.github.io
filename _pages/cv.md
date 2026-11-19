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
* **PhD in Mathematics**, University of Stuttgart & University of Münster, since 04/2026
  * Supervisors: [Prof. Dr. Bernard Haasdonk](https://www.ians.uni-stuttgart.de/institute/team/Haasdonk-00002/) (Stuttgart) and [Prof. Dr. Mario Ohlberger](https://www.uni-muenster.de/AMM/en/ohlberger/team/mario_ohlberger.shtml) (Münster)
* **M.Sc. in Mathematics**, University of Münster, 04/2024 – 03/2026
  * Thesis: *Model order reduction using group convolutional autoencoders*
  * Supervisors: Prof. Dr. Mario Ohlberger and Dr. Stephan Rave
* **B.Sc. in Simulation Technology**, University of Stuttgart, 10/2019 – 09/2023
  * Thesis: *TODO: thesis title*
  * Final grade: *TODO*

Software
======
* One of the main developers of [pyMOR](https://pymor.org), Model Order Reduction with Python

Publications
======
{% for post in site.publications reversed %}
  {% include publication-entry.html post=post %}
{% endfor %}
