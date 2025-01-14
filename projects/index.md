---
title: Projects
nav:
  order: 2
  tooltip: 수행 과제
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

## 2025 Activated

{% include list.html component="card" data="projects" filter="group == 'featured'" style="small" %}

{% include section.html %}

## Deactivated

{% include list.html component="card" data="projects" filter="!group" style="small" %}
