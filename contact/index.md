---
title: Contact
nav:
  order: 5
  tooltip: 연락처
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

SELAB은 경기도 안산시 한양대학로 55의 학연산클러스터지원센터 621호에, Scott Uk-Jin Lee 교수님의 연구실은 617호에 위치합니다. 

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
  image="images/photo.jpg"
  caption="SELAB"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="SELAB"
%}

{% endcapture %}

{% capture col3 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="SELAB"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}

{% include section.html dark=true %}

{% capture col1 %}
가나다라 테스트
{% endcapture %}

{% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
