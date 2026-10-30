---
permalink: /
title: "Yu Wang"
excerpt: "Research in generative modeling and AI for molecular science."
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

## About Me

I am a Ph.D. student in Artificial Intelligence at the **School of Computer Science, Peking University**, beginning in 2024. My background spans chemistry and computer science, and my research focuses on **AI for Science**, particularly generative modeling, molecular representation learning, and data-driven molecular and spectral analysis.

I have been a Research Intern at the **Tencent AI for Life Science Lab** since July 2025. Previously, I received my master's degree in Software Engineering and bachelor's degree in Chemistry from Shandong University.

## Research Interests

- **Generative models:** flow matching, diffusion models, and molecular design.
- **Molecular representation learning:** graph neural networks, chemical language models, and structured molecular data.
- **AI for Science:** retrosynthesis, molecular and mass-spectral analysis, and biochemical modeling.

## Education

- **Ph.D. in Artificial Intelligence**, School of Computer Science, Peking University (2024–2028, expected).
- **M.Eng. in Software Engineering**, Shandong University (2021–2024; rank 1/56).
- **B.Sc. in Chemistry**, Shandong University (2017–2021; rank 6/82).

## Research Experience

- **Research Intern**, Tencent AI for Life Science Lab (July 2025–present).

## Selected Publications

{% for paper in site.data.publications %}
{% if paper.featured %}
<div class="publication-entry">
    <div class="publication-title"><a href="{{ paper.url | escape }}">{{ paper.title | escape }}</a></div>
    <div class="publication-authors">{{ paper.authors }}</div>
    <div class="publication-venue">{{ paper.venue | escape }} · {{ paper.year }}</div>
    <div class="publication-links"><a href="{{ paper.url | escape }}">Paper</a>{% if paper.code %}<a href="{{ paper.code | escape }}">Code</a>{% endif %}</div>
  </div>
{% endif %}
{% endfor %}

[**View all publications →**](/publications/) · [Google Scholar](https://scholar.google.com/citations?user=wI8WU6kAAAAJ)

*Only publicly available articles and preprints are listed. For the latest citation metrics, please visit Google Scholar.*
