---
layout: single
author_profile: true
---

### Welcome!  

I am **Danilo Croce**, **Associate Professor** (*SSD INFO-01/A, ex INF/01 – Computer Science*) in the 
[Department of Enterprise Engineering](https://dii.uniroma2.it/) at the [University of Rome “Tor Vergata”](http://web.uniroma2.it/).

I am a researcher in **Machine Learning** and **Artificial Intelligence**, with a focus on  
**Natural Language Processing**, **Multimodality**, and **Ethics in AI**.  My work combines **theoretical models** with **large-scale applications**, aiming for methods that are  
**transparent**, **sustainable**, and impactful in real-world domains such as:  

- Language Models and Generative AI  
- Semantic Search and Retrieval-Augmented Generation  
- Human–Robot Interaction  
- Social Media and Opinion Mining  
- Digital Tourism, Healthcare, and Public Safety  

---

## Quick Links
- [About me](/about/)  
- [Publications](/publications/)  
- [Teaching](/teaching/)  
- [Curriculum Vitae](/files/croce_cv_may2025_eng.pdf)  


---

### Recent Posts
<ul>
{% for post in site.posts limit:3 %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a> - {{ post.date | date: "%b %e, %Y" }}
  </li>
{% endfor %}
</ul>

<p style="margin-top:.5rem;">
  <a class="btn btn--primary" href="{{ '/year-archive/' | relative_url }}">All posts →</a>
</p>