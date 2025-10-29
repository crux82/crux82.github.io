---
layout: single
author_profile: true
---

I am **Danilo Croce**, **Associate Professor** (*SSD INFO-01/A, ex INF/01 – Computer Science*) in the 
[Department of Enterprise Engineering](https://dii.uniroma2.it/) at the [University of Rome “Tor Vergata”](http://web.uniroma2.it/).

My research lies at the intersection of **Machine Learning**, **Natural Language Processing**, and **Multimodality**, with a strong focus on **transparency**, **sustainability**, and real-world impact.  
It combines **theoretical models** with **large-scale applications** across domains such as:

- Large Language Models and Generative AI  
- Semantic Search and Retrieval-Augmented Generation  
- Multimodality and Human–Robot Interaction  
- Applied AI in healthcare, tourism, and public safety  

## Quick Links
[About me](/about/) · [Publications](/publications/) · [Teaching](/teaching/) · [CV](/files/croce_cv_oct2025_ita.pdf)

## Recent Posts
<ul>
{% for post in site.posts limit:3 %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a> – {{ post.date | date: "%b %e, %Y" }}
  </li>
{% endfor %}
</ul>

<p style="margin-top:.5rem; text-align:center;">
  <a class="btn btn--primary" href="{{ '/year-archive/' | relative_url }}">All posts →</a>
</p>