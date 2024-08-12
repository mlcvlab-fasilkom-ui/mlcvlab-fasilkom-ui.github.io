---
title: Resources
nav:
  order: 4
  tooltip: Software, codes, datasets, products, courses, and more
---

# {% include icon.html icon="fa-solid fa-wrench" %}Resources

Software, codes, datasets, and other products from our research works and projects.

{%
  include button.html
  type="github"
  link="MLCV-Lab-Fasilkom-UI"
  icon="fa-brands fa-github"
  text="Follow us on GitHub"
  tooltip="Follow us on GitHub for new repositories"
%}

{% include tags.html tags="software, codes, datasets, courses, books" %}

{% include search-info.html %}

{% include section.html %}
## Software
{% include list.html component="card" data="resources" filters="group: software" %}

{% include section.html %}
## Codes & Repositories
{% include list.html component="card" data="resources" filters="group: codes" %}

{% include section.html %}
## Datasets
{% include list.html component="card" data="resources" filters="group: datasets" %}

{% include section.html %}
## Courses & Presentations
{% include list.html component="card" data="resources" filters="group: courses, presentations" style="small" %}

{% include section.html %}
## Books & Writings
{% include list.html component="card" data="resources" filters="group: books, writings" style="small" %}
