---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume/
---

## Research Profile

I am a Ph.D. student in Artificial Intelligence at Peking University, with training in both chemistry and computer science. My research covers **generative molecular design and property-guided optimization**, chemistry-informed molecular representation learning, drug property and toxicity prediction, **biomedical LLM post-training and genomic sequence modeling**, interpretable retrosynthesis, and molecular spectroscopy.

## Education

- **Peking University**, Ph.D. in Artificial Intelligence, School of Computer Science. September 2024–June 2028 (expected).
- **Shandong University**, M.Eng. in Software Engineering (Artificial Intelligence). September 2021–June 2024. Rank: 1/56.
- **Shandong University**, B.Sc. in Chemistry. September 2017–June 2021. Rank: 6/82.

## Research Experience

- **Tencent AI for Life Science Lab**, Research Intern. July 2025–present.

## Research Interests

Generative molecular modeling; drug-like molecule optimization; molecular property prediction; biomedical LLM fine-tuning; genomic sequence modeling; chemical representations; retrosynthesis; molecular spectroscopy.

## Selected Publications

{% for paper in site.data.publications %}
{% if paper.featured %}
- **[{{ paper.title | escape }}]({{ paper.url }})**, {{ paper.venue | escape }} ({{ paper.year }}).
{% endif %}
{% endfor %}

[Complete publication list](/publications/) · [Google Scholar](https://scholar.google.com/citations?user=wI8WU6kAAAAJ)
