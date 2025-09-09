---
layout: single
title: "Danilo Croce"
author_profile: true
---

Welcome!  
I am **Danilo Croce**, Associate Professor at the University of Rome “Tor Vergata”.  
My research lies at the intersection of **Natural Language Processing, Large Language Models (LLMs), Machine Learning, Information Retrieval, Human–Robot Interaction, and Multimodality**.

I lead the [Semantic Analytics Group (SAG)](http://sag.art.uniroma2.it) and I am a member of the **Artificial Intelligence at Tor Vergata (ART)** research group.

My work spans from the **theoretical foundations of semantic learning** to the **development of large-scale intelligent systems**, with strong emphasis on **epistemological transparency, ethics in AI, and multimodality**.

---

### Explore
<a class="btn" href="{{ '/about/' | relative_url }}">About</a>
<a class="btn" href="{{ '/teaching/' | relative_url }}">Teaching</a>
<a class="btn" href="{{ '/projects/' | relative_url }}">Projects</a>
<a class="btn" href="{{ '/software/' | relative_url }}">Software & Resources</a>
<a class="btn" href="{{ '/awards/' | relative_url }}">Awards</a>
<a class="btn" href="{{ '/service/' | relative_url }}">Service</a>
<a class="btn" href="{{ '/contact/' | relative_url }}">Contact</a>
<a class="btn" href="{{ '/publications/' | relative_url }}">Publications</a>

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