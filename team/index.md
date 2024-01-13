---
title: Team
nav:
  order: 3
  tooltip: About our team
---

{:.center}
# {% include icon.html icon="fa-solid fa-users" %}Team
maybe small parag.



{% include section.html %}
{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: phd" %}
{% include list.html data="members" component="portrait" filters="role: researcher" %}
{% include list.html data="members" component="portrait" filters="role: master" %}
{% include list.html data="members" component="portrait" filters="role: bachelor" %}



{% include section.html background="images/background.jpg" dark=true %}
maybe something for prospective students



{% include section.html %}
{:.center}
## Alumni
{% include list.html data="members" component="portrait" filters="role: alumni" %}
