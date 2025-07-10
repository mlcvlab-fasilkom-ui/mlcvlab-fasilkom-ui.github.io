---
title: Resources
nav:
  order: 4
  tooltip: Software, codes, datasets, products, courses, and more
---

# {% include icon.html icon="fa-solid fa-wrench" %}Resources

_Last modified on {% last_modified_at %A %d %B %Y %}_

Software, codes, datasets, and other products from our research works and projects.

{%
  include button.html
  type="github"
  link="MLCV-Lab-Fasilkom-UI"
  icon="fa-brands fa-github"
  text="Follow us on GitHub"
  tooltip="Follow us on GitHub for new repositories"
%}

{% include section.html %}

{% include tags.html tags="software, codes, datasets, courses, books" %}
{% include tags.html tags=site.tags %}

{% include search-box.html %}
{% include search-info.html %}

## Software
{% include list.html component="card" data="resources" filter="group == 'software'" %}

{% include section.html %}
## Codes & Repositories
{% include list.html component="card" data="resources" filter="group == 'codes'" %}

{% include section.html %}
## Datasets
{% include list.html component="card" data="resources" filter="group == 'datasets'" %}

{% include section.html %}
## Courses & Presentations
{% include list.html component="card" data="resources" filter="group == 'courses' or 'presentations'" style="small" %}

{% include section.html %}
## Books & Writings
{% include list.html component="card" data="resources" filter="group == 'books' or 'writings'" style="small" %}
