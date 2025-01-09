---
title: NEWS
nav:
  order: 3
  tooltip: 연구실 소식
---

# {% include icon.html icon="fa-solid fa-feather-pointed" %}News

{% include search-box.html %}

{% include tags.html tags=site.tags %}

{% include search-info.html %}

{% include list.html data="posts" component="post-excerpt" %}
