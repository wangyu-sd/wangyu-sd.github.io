---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume/
---

## Education

- **Peking University**, Ph.D. in Artificial Intelligence, School of Computer Science. September 2024–June 2028 (expected).
- **Shandong University**, M.Eng. in Software Engineering (Artificial Intelligence). September 2021–June 2024. Rank: 1/56.
- **Shandong University**, B.Sc. in Chemistry. September 2017–June 2021. Rank: 6/82.

## Research Experience

- **Tencent AI for Life Science Lab**, Research Intern. July 2025–present.

## Research Interests

Generative models; molecular representation learning; graph neural networks; large language models for scientific applications; retrosynthesis and molecular-spectral modeling.

## Selected Publications

{% for paper in site.data.publications %}
{% if paper.featured %}
- **[{{ paper.title | escape }}]({{ paper.url }})**, {{ paper.venue | escape }} ({{ paper.year }}).
{% endif %}
{% endfor %}

[Complete publication list](/publications/) · [Google Scholar](https://scholar.google.com/citations?user=wI8WU6kAAAAJ)
