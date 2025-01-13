---
title: Team
nav:
  order: 4
  tooltip: 구성원
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include section.html %}

{% include list.html data="members" component="portrait" filter="role != 'pi' and group != 'alum'" %}
{% include section.html %}

# {% include icon.html icon="fa-solid fa-users" %}Alumni
{% include list.html data="members" component="portrait" filter="role != 'pi' and group == 'alum'" %}
{% include section.html %}
