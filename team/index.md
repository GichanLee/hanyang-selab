---
title: Team
nav:
  order: 4
  tooltip: 구성원
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include section.html %}

{% include list.html data="members" component="portrait" filter="role != 'pi' and group == '현역'" %}
{% include section.html %}

# {% include icon.html icon="fa-solid fa-users" %}Alumni (master)
{% include list.html data="members" component="portrait" filter="role != 'pi' and group == '석사졸'" %}
{% include section.html %}

# {% include icon.html icon="fa-solid fa-users" %}Alumni (phd)
{% include list.html data="members" component="portrait" filter="role != 'pi' and group == '박사졸'" %}
{% include section.html %}
