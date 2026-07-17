---
layout: archive
title: "CV"
permalink: /cv/
author_profile: false
redirect_from:
  - /resume
---

{% include base_path %}

<section class="cv-education">
  <h1 id="education">Education</h1>
  <ol class="cv-education__timeline">
    <li class="cv-education__entry">
      <time datetime="2023">2023–Present</time>
      <div class="cv-education__detail">
        <h2>PhD in Data Science</h2>
        <p>City University of Hong Kong · Hong Kong SAR</p>
      </div>
    </li>
    <li class="cv-education__entry">
      <time datetime="2021">2021–2023</time>
      <div class="cv-education__detail">
        <h2>MSc in Applied Mathematics for Science and Technology</h2>
        <p>The Hong Kong Polytechnic University · Hong Kong SAR</p>
      </div>
    </li>
    <li class="cv-education__entry">
      <time datetime="2016">2016–2020</time>
      <div class="cv-education__detail">
        <h2>Bachelor's degree</h2>
        <p>Sichuan University · Financial Engineering major · Software Engineering minor</p>
      </div>
    </li>
  </ol>
</section>

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
