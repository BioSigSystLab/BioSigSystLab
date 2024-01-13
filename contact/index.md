---
title: Contact
nav:
  order: 4
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact
Some text!

{%
  include button.html
  type="email"
  text="jane@smith.com"
  link="jane@smith.com"
%}
{%
  include button.html
  type="phone"
  text="(555) 867-5309"
  link="+1-555-867-5309"
%}



{% include section.html %}
{:.center}
## Mailing Address
Lab Location
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps"
%}

{% capture col1 %}
{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}
{% endcapture %}

{% capture col2 %}
{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}
{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

