---
title: Contact
nav:
  order: 5
  tooltip: 연락처
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

SELAB에 대하여 궁금한 사항들은 아래의 연락처로 연락 바랍니다.

{%
  include button.html
  type="email"
  text="scottlee@hanyang.ac.kr"
  link="scottlee@hanyang.ac.kr"
%}
{%
  include button.html
  type="phone"
  text="(031) 867-5309"
  link="+82-031-867-5309"
%}
{%
  include button.html
  type="address"
  tooltip="한양대 ERICA 학연산클러스터지원센터"
  link="https://maps.app.goo.gl/id7bQnzffGXXaXG17"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/cluster.jpg"
  caption="학연산클러스터"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="SELAB"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}
