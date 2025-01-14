---
title: Projects
nav:
  order: 2
  tooltip: 수행 과제
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects
## 2025 Activated
{% include tags.html tags="pi, ci" link="/hanyang-selab/projects/" %}


{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## Deactivated

{% include list.html component="card" data="projects" filter="!group" style="small" %}
