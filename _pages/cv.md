---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

Get my detailed CV [here](/files/shambhavi postdoc cv.pdf).

Education
======

* Ph.D in Statistics, Banaras Hindu University , 2025 (Analysis of Human Fertility Patterns Using Bayesian Paradigm)
* M.Sc. in Statistics, 2019
* B.Sc. in Statistics, 2017

Courses studied
======

* Real Analysis
* Measure theory and Probability
* Linear Algebra
* Sample Survey and Statistics for National Development
* Distribution Theory and Non Parametric Inference
* Linear Models and Regression Analysis
* Statistical Computing (C, C++, JAVA, R, SPSS)
* Statistical Inference
* Design and Analysis of Experiments
* Reliability
* Stochastic Processes
* Multivariate Analysis
* Demography
  
Skills
======

* Bayesian data analysis
* R programming
* MCMC simulation techniques
* Scientific writing

Awards and Recognitions
======

* Best Paper Award at the International Conference on Recent Developments in the Techniques of Bayesian Paradigm held at BHU, January 2025.
* INSPIRE Fellowship: Awarded by the Department of Science and Technology (DST), Government of India.
* Junior Research Fellowship (JRF): Awarded by the University Grants Commission (UGC) in July 2022.
* AIR-79 in GATE (Statistics) 2020: Awarded by the National Coordination Board (NCB) for the Department of Higher Education, MHRD, Government of India.
* Gold Medal: Awarded by Patna University for securing first rank in M.Sc. Statistics.
* Student Member, Internal Quality Assurance Cell (NAAC), Patna University.

Publications
======

<p style="font-size: 0.9em; margin-top: -1em;">
  🔗 For details, visit the <a href="/publications" target="_blank">Publications page</a>.
</p>

{% for post in site.publications reversed %}
<div style="margin-bottom: 1.5em;">
  <strong>{{ post.title }}</strong><br>
  <span style="font-size: 0.95em;">
    {{ post.citation | markdownify }}
  </span><br>
  {% if post.paperurl %}
    📄 <a href="{{ post.paperurl }}" target="_blank">Read paper</a>
  {% endif %}
</div>
{% endfor %}



Talks and Presentations
======

{% for post in site.talks reversed %}
<div style="margin-bottom: 1.2em;">
  <strong>{{ post.title }}</strong><br>
  🗓️ <em>{{ post.date | date: "%B %Y" }}</em><br>
  {% if post.excerpt %}
    <span style="font-size: 0.95em;">{{ post.excerpt | markdownify }}</span><br>
  {% endif %}
  {% if post.slides %}
    🎤 <a href="{{ post.slides }}" target="_blank">View slides</a>
  {% endif %}
</div>
{% endfor %}



