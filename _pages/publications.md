
---
layout: single
title: "Publications"
permalink: /publications/
author_profile: true
---

This list is automatically generated from my BibTeX file.

- Show all:  
  {% raw %}{% bibliography %}{% endraw %}

- Recent years:  
  {% raw %}{% bibliography --query @*[year>=2022] %}{% endraw %}

- By type (examples):  
  - Journals: {% raw %}{% bibliography --query @article %}{% endraw %}  
  - Conferences: {% raw %}{% bibliography --query @inproceedings %}{% endraw %}

> To update, replace `_bibliography/references.bib` with your BibTeX.
