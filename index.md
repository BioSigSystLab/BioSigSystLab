---
title: Home
---

# BSSA's Website

An engaging 1-3 sentence description of our lab.



{:.center}
{% include section.html full=true %}
{% include banner.html image="images/banner.jpg" %}
{% include section.html %}



# Highlights


{% capture text %}
description of our research theme
{%
  include button.html
  link="research"
  text="See our research projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}
{% endcapture %}
{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Our Research"
  text=text
%}



{% capture text %}
description of current projects
{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}
{% endcapture %}
{%
  include feature.html
  image="images/photo.jpg"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}



{% capture text %}
Something for Team members
{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}
{% endcapture %}
{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=text
%}


