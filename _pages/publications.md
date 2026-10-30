---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

This list is based on my [Google Scholar profile](https://scholar.google.com/citations?user=wI8WU6kAAAAJ) and publisher records. Published versions are preferred over duplicate preprints. Citation counts are maintained by Google Scholar.

{% assign previous_year = 0 %}
{% for paper in site.data.publications %}
  {% if paper.year != previous_year %}
    <h2>{{ paper.year }}</h2>
    {% assign previous_year = paper.year %}
  {% endif %}
  {% include publication-card.html paper=paper %}
{% endfor %}

*For the most up-to-date record, see [Google Scholar](https://scholar.google.com/citations?user=wI8WU6kAAAAJ).*
