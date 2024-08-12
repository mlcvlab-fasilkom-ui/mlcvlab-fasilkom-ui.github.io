---
title: Member
nav:
  order: 1
  tooltip: Our lab members
---

# {% include icon.html icon="fa-solid fa-users" %}Member

The MLCV lab at Fasilkom UI consists of lecturers with active research interests in machine learning, computer vision, and image processing. It is led by a head of the lab and a director. For more information, please check each researcher's personal profile on the Fasilkom website, which is linked to each profile.

{% include section.html %}
## Head of Lab and Director
{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: dir" %}

{% include section.html %}
## Researcher
{% include list.html data="members" component="portrait" filters="role: researcher" %}

{% include section.html %}
## Featured Resources
{% include list.html component="card" data="resources" filters="group: featured" %}
