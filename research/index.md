---
title: Research Topic & Project
nav:
  order: 3
  tooltip: Research Topic & Project
---

# {% include icon.html icon="fa-solid fa-wrench" %}Research Topic & Project

_Last modified on {% last_modified_at %A %d %B %Y %}_

{% capture col1 %}
{%
  include figure.html
  image="images/Projects.jpg"
  link="images/Projects.jpg"
  caption="Projects in MLCV Lab"
%}
{% endcapture %}

{% capture col2 %}
{%
  include figure.html
  image="images/Topics.jpg"
  link="images/Topics.jpg"
  caption="Research Topics in MLCV Lab"
%}
{% endcapture %}
{% include cols.html col1=col1 col2=col2 %}

{% include tags.html tags="Computer Vision, NLP, ML/DL, Biomedical, Social Science, Life Science" %}

{% include search-info.html %}

{% include section.html %}
## Current Research Projects
**Under construction**
{% include list.html component="card" data="projects" filters="group: featured" %}

{% include section.html %}
## Past Research Projects
**Under construction**
{% include list.html component="card" data="projects" filters="group: " style="small" %}
