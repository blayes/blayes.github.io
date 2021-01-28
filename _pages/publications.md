---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Research Interests
======
I am broadly interested in developing Bayesian methods that are computationally efficient and have theoretical guarantees. My recent work is focused on developing flexible Bayesian methods and efficient computational algorithms for big data sets, tailored for both their complexity and size. Motivating examples include big data in genomics, geostatistics, and biomedical databases. Simultaneously optimizing for the size and complexity is a challenge with current Bayesian methods. I am developing novel and computationally tractable Bayesian methods using principles from machine learning and asymptotic Bayesian statistics. 

Divide-and-Conquer Bayesian Inference
------

Gaussian Process
------



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
