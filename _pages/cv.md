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
* Ph.D in Computer Science, University, 2025 (expected)
* M.S. in Computer Science, University, 2022
* B.S. in Computer Science, University, 2020

Work experience
======
* 2023 - Present: Research Assistant
  * University
  * Duties includes: LLM research and development
  * Supervisor: Professor

Skills
======
* Large Language Models
* Machine Learning
* Natural Language Processing
* Python
* PyTorch

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

Service and leadership
======
* Reviewer, LCFM 2025 (Long Context Foundation Models Workshop)
* Program Committee Member, COML 2025
