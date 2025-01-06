---
---

# Welcome to SELAB!

안녕하세요. 한양대학교 ERICA 캠퍼스의 소프트웨어 공학 연구실입니다. Scott Uk-Jin Lee 교수님의 지도 아래 6명의 석박사통합과정생들이 열심히 연구하고 있습니다:) 주요 연구 분야는 머신러닝/인공지능 기반의 소프트웨어 결함 예측 및 자동화 디버깅과 소프트웨어 테스팅입니다. 저희 연구실의 장점은 해외 연구실의 문화가 반영되어 출퇴근이 자유롭고, 연구 분야 및 주제도 원하는대로 선택할 수 있고, 구성원들의 사이가 제법 화목하다는 점입니다. 그러나, 그 누구도 무엇을 하라고 시키거나 리서치 패스를 정해주지 않기 때문에 수동적인 학생은 적응이 어려울 수 있습니다. 이 외에도 많은 것들이 있지만 놀러오셔서 물어보세요! 아무튼 환영합니다! 하이!!

{% include section.html %}

## 자랑

{% capture text %}

우리는 이러고 놀아요!

{%
  include button.html
  link="research"
  text="주요 연구"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="SELAB의 연구방향성"
  text=text
%}

{% capture text %}

이런걸로 생활할 돈을 좀 법니다!

{%
  include button.html
  link="projects"
  text="주요 프로젝트"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="projects"
  title="SELAB의 소중한 프로젝트들"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

학연산클러스터 621호엔 이런 사람들이 살아요!

{%
  include button.html
  link="team"
  text="구성원 구경"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="구성원"
  text=text
%}
