---
permalink: /
title: "Yu Wang"
excerpt: "Generative molecular modeling, biomedical LLM fine-tuning, genomics, and AI for Science."
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

## About Me

I am a Ph.D. student in Artificial Intelligence at the **School of Computer Science, Peking University**, and a Research Intern at **Tencent AI for Life Science Lab**. With interdisciplinary training in chemistry and computer science, I study **generative modeling, molecular design, and AI for Science**.

My research spans **molecular generation and property-guided optimization**, molecular property and toxicity prediction, **biomedical LLM post-training and genomic representation learning**, interpretable retrosynthesis, and molecular-spectral analysis. I am particularly interested in combining chemical priors and learned representations to support reliable molecular design and structure elucidation.

## News

- **October 2026 · NeurIPS 2026** — Three papers accepted as posters: [MolSpecFlow](https://openreview.net/forum?id=me61FbJpyy) (molecular–spectral learning), [Balanced Fine-Tuning](https://openreview.net/forum?id=p2HWge7bRt) (biomedical LLMs), and [WaveSem](https://neurips.cc/Downloads/2026) (genomic sequence modeling).
- **July 2026 · Nature Communications** — [Navigating chemical-linguistic sharing space with heterogeneous molecular encoding](https://doi.org/10.1038/s41467-026-74666-w).
- **May 2026 · Nature Communications** — [Learning the PTM code through a coarse-to-fine mechanism-aware framework](https://doi.org/10.1038/s41467-026-73148-3).
- **May 2025 · Nature Communications** — [A self-conformation-aware pre-training framework for molecular property prediction with substructure interpretability](https://doi.org/10.1038/s41467-025-59634-0).
- **January 2025 · Nature Computational Science** — [Decoupled peak property learning for efficient and interpretable electronic circular dichroism spectrum prediction](https://doi.org/10.1038/s43588-024-00757-7).
- **October 2023 · Nature Communications** — [Retrosynthesis prediction with an interpretable deep-learning framework based on molecular assembly tasks](https://doi.org/10.1038/s41467-023-41698-5).

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
    <p class="research-theme__links"><a href="https://doi.org/10.1038/s41467-025-59634-0">SCAGE</a> <span>·</span> <a href="https://doi.org/10.1016/j.compbiomed.2023.106904">MolFPG</a></p>
  </div>
  <div class="research-theme">
    <h3>Biomedical LLM Post-training</h3>
    <p>Methods for aligning language models with biomedical knowledge through fine-tuning on sparse, knowledge-intensive scientific data.</p>
    <p class="research-theme__links"><a href="https://openreview.net/forum?id=p2HWge7bRt">Balanced Fine-Tuning · NeurIPS 2026</a></p>
  </div>
  <div class="research-theme">
    <h3>Genomic Sequence Modeling</h3>
    <p>Adaptive tokenization and representation learning for genomic foundation models, disentangling biological signals from sequence-level noise.</p>
    <p class="research-theme__links"><a href="https://neurips.cc/Downloads/2026">WaveSem · NeurIPS 2026</a></p>
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
{% include publication-card.html paper=paper %}
{% endif %}
{% endfor %}

[**View all publications →**](/publications/) · [Google Scholar](https://scholar.google.com/citations?user=wI8WU6kAAAAJ)

*Only publicly available articles and preprints are listed. For the latest citation metrics, please visit Google Scholar.*
