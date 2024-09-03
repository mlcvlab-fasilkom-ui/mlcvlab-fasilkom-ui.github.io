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
| Pattern Recognition | :white_check_mark: | :white_check_mark: | :white_check_mark: |   :white_check_mark: | :white_check_mark: |   | :white_check_mark: |   :white_check_mark: | :white_check_mark: |   |   |   :white_check_mark: | :white_check_mark: | 10
| Image Processing  | :white_check_mark: | :white_check_mark: | :white_check_mark: |   :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: |   :white_check_mark: | :white_check_mark: |   |   |   :white_check_mark: |   | 10
| Spatial Data Analysis |   | :white_check_mark: | :white_check_mark: |     | :white_check_mark: |   |   |   :white_check_mark: | :white_check_mark: |   |   |     |   | 5
| Machine and Deep Learning | :white_check_mark: | :white_check_mark: | :white_check_mark: |   :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: |   :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: |   :white_check_mark: | :white_check_mark: | 13
| Natural Language Processing  | :white_check_mark: |   |   |    |   | :white_check_mark: | :white_check_mark: |   |    |    |   |    |   | 3
| Large Language Model  | :white_check_mark: |   |   |    |   | :white_check_mark: | :white_check_mark: |   | :white_check_mark: |   |   |    |   | 3
| Social Signal Processing  | :white_check_mark: |    |   |    |    |    |   |    |    |   |   |   :white_check_mark: |   | 2
| Optimization  | :white_check_mark: |    |   |    |    |    |   |    |    |   |   |   :white_check_mark: | :white_check_mark: | 4
| Knowledge Graphs  | :white_check_mark: |    |   |    |    |    |   |    |    |   |   |     |   | 1
| Video Processing  | :white_check_mark: |   |   |   :white_check_mark: | :white_check_mark: |   | :white_check_mark: | :white_check_mark: | :white_check_mark: |   |   |   |   | 6
| Optics and Photometry  |   |   |   |   |   |   |   |   :white_check_mark: |   |   |   |   |   | 1
| Biomedical Image Computation and Analysis  | :white_check_mark: |   |   |   | :white_check_mark: |   |   |   | :white_check_mark: |   | :white_check_mark: |     |   | 4
| Speech Processing  |   |   |   |   |   |   | :white_check_mark: |   |   |   |   |   |   | 1
| Reinforcement Learning  | :white_check_mark: |   |   |   |   |   |   |   | :white_check_mark: |   |   |   | :white_check_mark: | 3
| Embodied AI (Robotics)  |   |   |   |   | :white_check_mark: |   |   |   |   |   |   |   | :white_check_mark: | 2
| Applied ML  | :white_check_mark: |   | :white_check_mark: |   |   |   |   |   | :white_check_mark: | :white_check_mark: |   |   :white_check_mark: | :white_check_mark: | 6
| Biomedical Engineering  | :white_check_mark: |   |   |   | :white_check_mark: |    |   |   | :white_check_mark: | :white_check_mark: |   |   |   | 4
| Computational Neuroscience  |   |   |   |   |   |   |   |   |   | :white_check_mark: |    |   |   | 1
| Applied Computer Vision  | :white_check_mark: |   | :white_check_mark: |   | :white_check_mark: |   |   | :white_check_mark: | :white_check_mark: |   |   |     |   | 5
| Computer Vision  | :white_check_mark: | :white_check_mark: | :white_check_mark: |   :white_check_mark: | :white_check_mark: |   | :white_check_mark: | :white_check_mark: | :white_check_mark: |   |   |   :white_check_mark: |   | 9
| Bioinformatics  |   |   |   |   | :white_check_mark: |   |   | :white_check_mark: | :white_check_mark: |   |   | :white_check_mark: | :white_check_mark: | 5
| Human Motion and Gait Analysis |   |   |   |   | :white_check_mark: | :white_check_mark: | :white_check_mark: |   | :white_check_mark: |   |   | :white_check_mark: |   | 5
| Biometric Recognition  |   | :white_check_mark: |   |   | :white_check_mark: |   | :white_check_mark: | :white_check_mark: |   |   |   |:white_check_mark: |   | 5
| Spoof Recognition  |   | :white_check_mark: |   |   | :white_check_mark: |   |   |   |   |   |   |   |   | 2
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
