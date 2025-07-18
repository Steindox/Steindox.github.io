---
permalink: /
title: "Tianlai Jin - Research in Efficient AI"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Welcome to my academic website! I am an undergraduate student at Southern University of Science and Technology (SUSTech), advised by Prof. Hao Yu. My research focuses on efficient AI, model compression, hardware acceleration, and foundation model optimization.

I am passionate about working at the intersection of algorithms and hardware, developing practical solutions for real-world AI applications. Currently, I am seeking PhD opportunities for Fall 2026 to further explore these research directions.

## Research Interests
- **Model Compression**: Developing efficient pruning and quantization techniques for large language models
- **Hardware Acceleration**: Optimizing AI models for deployment on various hardware platforms
- **Foundation Model Optimization**: Improving the efficiency and performance of foundation models
- **Algorithm-Hardware Co-design**: Exploring the intersection of algorithmic improvements and hardware optimization

## Current Work
My current research focuses on developing novel pruning frameworks for large language models, with a particular interest in one-shot pruning techniques that can efficiently reduce model size while maintaining performance.

## Publications
{% for post in site.publications reversed %}
  <div class="publication-item">
    <h3><a href="{{ post.website }}">{{ post.title }}</a></h3>
    <p><strong>{{ post.publisher }}</strong> • {{ post.releaseDate | date: "%B %Y" }}</p>
    <p>{{ post.summary }}</p>
  </div>
{% endfor %}

## Contact
Feel free to reach out if you're interested in collaborating or have questions about my research!
