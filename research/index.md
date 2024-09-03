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


| Topic/Interest | [AAK](team/adila-krisnadhi.html) | AM | AYA | DC | DNU | ER | KA | LR | MFR | NF | SN | TB | VD | Total
| :---- | :----: | :----: | :----: | :----: | :----: | :----: | :----: | :----: | :----: | :----: | :----: | :----: |:----: | :----: |
| Pattern Recognition | &check; | &check; | &check; |   &check; | &check; |   | &check; |   &check; | &check; |   |   |   &check; | &check; | 10
| Image Processing  | &check; | &check; | &check; |   &check; | &check; | &check; | &check; |   &check; | &check; |   |   |   &check; |   | 10
| Spatial Data Analysis |   | &check; | &check; |     | &check; |   |   |   &check; | &check; |   |   |     |   | 5
| Machine and Deep Learning | &check; | &check; | &check; |   &check; | &check; | &check; | &check; |   &check; | &check; | &check; | &check; |   &check; | &check; | 13
| Natural Language Processing  | &check; |   |   |    |   | &check; | &check; |   |    |    |   |    |   | 3
| Large Language Model  | &check; |   |   |    |   | &check; | &check; |   | &check; |   |   |    |   | 3
| Social Signal Processing  | &check; |    |   |    |    |    |   |    |    |   |   |   &check; |   | 2
| Optimization  | &check; |    |   |    |    |    |   |    |    |   |   |   &check; | &check; | 4
| Knowledge Graphs  | &check; |    |   |    |    |    |   |    |    |   |   |     |   | 1
| Video Processing  | &check; |   |   |   &check; | &check; |   | &check; | &check; | &check; |   |   |   |   | 6
| Optics and Photometry  |   |   |   |   |   |   |   |   &check; |   |   |   |   |   | 1
| Biomedical Image Computation and Analysis  | &check; |   |   |   | &check; |   |   |   | &check; |   | &check; |     |   | 4
| Speech Processing  |   |   |   |   |   |   | &check; |   |   |   |   |   |   | 1
| Reinforcement Learning  | &check; |   |   |   |   |   |   |   | &check; |   |   |   | &check; | 3
| Embodied AI (Robotics)  |   |   |   |   | &check; |   |   |   |   |   |   |   | &check; | 2
| Applied ML  | &check; |   | &check; |   |   |   |   |   | &check; | &check; |   |   &check; | &check; | 6
| Biomedical Engineering  | &check; |   |   |   | &check; |    |   |   | &check; | &check; |   |   |   | 4
| Computational Neuroscience  |   |   |   |   |   |   |   |   |   | &check; |    |   |   | 1
| Applied Computer Vision  | &check; |   | &check; |   | &check; |   |   | &check; | &check; |   |   |     |   | 5
| Computer Vision  | &check; | &check; | &check; |   &check; | &check; |   | &check; | &check; | &check; |   |   |   &check; |   | 9
| Bioinformatics  |   |   |   |   | &check; |   |   | &check; | &check; |   |   | &check; | &check; | 5
| Human Motion and Gait Analysis |   |   |   |   | &check; | &check; | &check; |   | &check; |   |   | &check; |   | 5
| Biometric Recognition  |   | &check; |   |   | &check; |   | &check; | &check; |   |   |   |&check; |   | 5
| Spoof Recognition  |   | &check; |   |   | &check; |   |   |   |   |   |   |   |   | 2
| Total per member| 15 | 7 | 7 | 5 | 15 | 5 | 10 | 10 | 13 | 4 | 3 | 9 | 7 | 

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
