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
* B.S. in Microelectronics Engineering, Southern University of Science and Technology (SUSTech), 2020-2026 (expected)
  * Advisor: Prof. Hao Yu
  * Research Focus: Efficient AI, Model Compression, Hardware Acceleration

Skills
======
* **Programming Languages**: Python, C++, CUDA, PyTorch, TensorFlow
* **Research Areas**: Model Compression, Hardware Acceleration, Large Language Models, Neural Network Pruning, Foundation Models
* **Tools & Frameworks**: Git, Linux, Docker, Hugging Face, Transformers
* **Languages**: English, Mandarin

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
  
Interests
======
* Anime, Movie, Guitar
