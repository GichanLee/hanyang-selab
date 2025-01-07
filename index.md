---
---

# Welcome to SELAB!

안녕하세요? 한양대학교 ERICA 캠퍼스의 소프트웨어 공학 연구실 (SELAB)입니다! SELAB에서는 Scott Uk-Jin Lee 교수님의 지도 아래 (2025.01 기준) 현재 6명의 석박사통합과정생들이 소프트웨어공학에 관하여 흥미로운 주제를 탐색하고 그에 따라 다양한 연구들을 수행하고 있습니다. 현재 수행중인 연구들과 과제들, 구성원들은 다음과 같습니다.

{% include section.html %}

## SELAB Highlights

{% capture text %}

SELAB의 주요 연구 분야는 "머신러닝/인공지능 기반의 소프트웨어 결함 예측, 자동화 디버깅, 소프트웨어 테스팅"이지만, 저희는 소프트웨어 공학이라는 연구 분야 아래 모든 흥미로운 주제들에 열려있습니다.

{%
  include button.html
  link="research"
  text="Publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/graphs.png"
  link="research"
  title="Research"
  text=text
%}

{% capture text %}

이런걸로 생활할 돈을 좀 법니다!

{%
  include button.html
  link="projects"
  text="Outputs"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="projects"
  title="Project"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

학연산클러스터 621호엔 이런 사람들이 살아요!

{%
  include button.html
  link="team"
  text="구성원"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Team"
  text=text
%}
