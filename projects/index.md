---
title: Projects
nav:
  order: 2
  tooltip: 수행 과제
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

{% include tags.html tags="pi, ci" link="/projects/" %}
## Current (2025)
{% include list.html component="card" data="projects" filter="group == 'featured'" %}
{% include section.html %}

## Completed
{% include list.html component="card" data="projects" filter="!group" style="small" %}
