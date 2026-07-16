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
* **PhD in Data Science**, City University of Hong Kong, 2023-present. GPA: 3.71/4.3.
* **MSc in Applied Mathematics for Science and Technology**, The Hong Kong Polytechnic University, 2021-2023. GPA: 4.15/4.3.
* **Bachelor's degree**, Sichuan University, 2016-2020.
  * Financial Engineering (major), GPA: 3.58/4.0.
  * Software Engineering (minor), GPA: 3.53/4.0.

Publications and Working Papers
======
**Conference Papers**

<ul>{% for post in site.publications reversed %}
  {% if post.category == 'conferences' %}{% include archive-single-cv.html %}{% endif %}
{% endfor %}</ul>

**Working Papers**

<ul>{% for post in site.publications reversed %}
  {% if post.category == 'working_papers' %}{% include archive-single-cv.html %}{% endif %}
{% endfor %}</ul>
  
Academic Service
======
* Reviewer, *Optimization and Engineering*.
* Reviewer, AISTATS.

Teaching Experience
======
* Teaching Assistant, Optimization, Fall 2024.
* Teaching Assistant, Dynamic Programming and Reinforcement Learning, Spring and Fall 2025.
* Teaching Assistant, Stochastic Optimization for Machine Learning, Spring 2025.
* Teaching Assistant, Decision Analysis and Risk Management, Spring 2026.

Research Experience
======
* Research Assistant with Dr. Jiaqing Wei, high-dimensional trajectory compression, April-October 2022.
* Research Assistant with Prof. Chin Pang Ho, robust regret in Markov decision processes, January-May 2023.

Talks
======
<ul>{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html  %}
{% endfor %}</ul>

Industry Experience
======
**China Merchants Securities**, July-August 2019

* Supported the preparation and issuance of corporate bonds for issuers including Ford Motor Company and Powerlong Real Estate Holdings.
* Contributed to prospectus drafting, financial analysis, business analysis, and due diligence.

Awards and Qualifications
======
* Institutional Research Tuition Scholarship / Research Tuition Scholarship, 2025.
* Applied Mathematics Scholarship for Outstanding Taught Postgraduates, 2022.
* CFA Level I Exam passed, 2020.
* Software Engineering Dual Degree Scholarship, 2019 and 2020.
