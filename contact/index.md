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
  text="georgios.mitsis@mcgill.ca"
  link="georgios.mitsis@mcgill.ca"
%}
{%
  include button.html
  type="phone"
  text="(514) 398-4344"
  link="+1-514-398-4344"
%}



{% include section.html %}
{:.center}
## Mailing Address
{:.center}
817 Sherbrooke St W, Montreal, Quebec, H3A OC3

{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/5pqjBCWD3H9BFzrR6"
%}

{% capture col1 %}
{%
  include figure.html
  image="images/photo.jpg"
  caption="Picture of Lab"
%}
{% endcapture %}

{% capture col2 %}
{%
  include figure.html
  image="images/photo.jpg"
  caption="Picture of Lab members"
%}
{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

