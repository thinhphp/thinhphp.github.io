---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<h2 style="color:#87CEEB">Education</h2>
<hr>
**University of Science, VNUHCM**, 2018 - 2022\
Bachelor in *Computer Science*
* Thesis: Integrating Label Attention into CRF-Based Vietnamese\
Constituency Parser
* Advisor: Assoc. Prof. Dien Dinh
* GPA: 3.95/4.00, graduated with Excellent Degree

<h2 style="color:#87CEEB">Research experience</h2>
<hr>
**AI Resident | 2018 - present**\
*VinAI Research*, Vietnam
* Supervisor: Dr. Dat Quoc Nguyen
* Research topic: Spoken Language Understanding, Multimodality

<h2 style="color:#87CEEB">Publications</h2>
<hr>
  <ul>{% for post in site.publications reversed%}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!-- Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul> -->
  
<!-- Service and leadership
======
* Currently signed in to 43 different slack teams -->
