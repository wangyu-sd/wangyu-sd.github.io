---
permalink: /
title: "Yu Wang"
excerpt: "Generative molecular design, property optimization, and AI for Science."
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

## About Me

I am a Ph.D. student in Artificial Intelligence at the **School of Computer Science, Peking University**, and a Research Intern at **Tencent AI for Life Science Lab**. With interdisciplinary training in chemistry and computer science, I study **generative modeling, molecular design, and AI for Science**.

My research spans **molecular generation and property-guided optimization**, molecular property and toxicity prediction, chemical representation learning, interpretable retrosynthesis, and molecular-spectral analysis. I am particularly interested in combining chemical priors and learned representations to support reliable molecular design and structure elucidation.

## News

- **October 2026:** Our paper **[MolSpecFlow: Modality-Incomplete Molecular--Spectral Learning for MS/MS](https://openreview.net/forum?id=me61FbJpyy)** was accepted to **NeurIPS 2026**. [Earlier preprint](https://doi.org/10.64898/2026.01.28.702438).

## Research Areas

<div class="research-themes">
  <div class="research-theme">
    <h3>Generative Molecular Design &amp; Property Optimization</h3>
    <p>Generative approaches to drug-like molecule design and structural optimization under desired chemical properties, including multiview graph generation and score-based molecular inverse design.</p>
    <p class="research-theme__links"><a href="https://doi.org/10.1109/TNNLS.2024.3506619">MEDICO · IEEE TNNLS</a> <span>·</span> <a href="https://arxiv.org/abs/2409.07912">OrgMol-Design · ICASSP</a></p>
  </div>
  <div class="research-theme">
    <h3>Molecular Representation &amp; Property Prediction</h3>
    <p>Chemistry-informed graph representation learning for physicochemical properties and toxicity, incorporating reactivity, conformational, and molecular fingerprint information.</p>
    <p class="research-theme__links"><a href="https://doi.org/10.1016/j.compbiomed.2023.107666">MolCAP</a> <span>·</span> <a href="https://doi.org/10.1038/s41467-025-59634-0">SCAGE</a> <span>·</span> <a href="https://doi.org/10.1016/j.compbiomed.2023.106904">MolFPG</a></p>
  </div>
  <div class="research-theme">
    <h3>Retrosynthesis &amp; Chemical Reasoning</h3>
    <p>Interpretable retrosynthetic prediction through structured molecular assembly and chemically meaningful graph-based decision making.</p>
    <p class="research-theme__links"><a href="https://doi.org/10.1038/s41467-023-41698-5">RetroExplainer · Nature Communications</a></p>
  </div>
  <div class="research-theme">
    <h3>Molecular Spectroscopy &amp; Structure Elucidation</h3>
    <p>Molecular–spectral generative modeling and physics-informed spectral prediction, spanning tandem mass spectrometry and electronic circular dichroism.</p>
    <p class="research-theme__links"><a href="https://openreview.net/forum?id=me61FbJpyy">MolSpecFlow · NeurIPS 2026</a> <span>·</span> <a href="https://doi.org/10.1038/s43588-024-00757-7">ECD · Nature Computational Science</a></p>
  </div>
</div>

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
    <div class="publication-links"><a href="{{ paper.url | escape }}">Paper</a>{% if paper.preprint %}<a href="{{ paper.preprint | escape }}">Preprint</a>{% endif %}{% if paper.code %}<a href="{{ paper.code | escape }}">Code</a>{% endif %}</div>
  </div>
{% endif %}
{% endfor %}

[**View all publications →**](/publications/) · [Google Scholar](https://scholar.google.com/citations?user=wI8WU6kAAAAJ)

*Only publicly available articles and preprints are listed. For the latest citation metrics, please visit Google Scholar.*
