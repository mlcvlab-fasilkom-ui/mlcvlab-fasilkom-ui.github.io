---
title: Research
nav:
  order: 3
  tooltip: Research
---

# {% include icon.html icon="fa-solid fa-wrench" %}Topics

_Last modified on {% last_modified_at %A %d %B %Y %}_

{% include search-box.html %}
{% include search-info.html %}

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

{% include section.html %}

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

{% include tags.html tags="Computer Vision, NLP, machine learning, deep learning, Biomedical, Social Science, Life Science" %}
{% include tags.html tags=site.tags %}

## Current Research Projects
**Under construction**
{% include list.html component="card" data="projects" filters="group: featured" style="small" %}

{% include section.html %}
## Past Research Projects
**Under construction**
{% include list.html component="card" data="projects" filters="group: " style="small" %}
