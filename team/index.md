---
title: Member
nav:
  order: 3
  tooltip: Our members
---

# {% include icon.html icon="fa-solid fa-users" %}Member

The members of MLCV lab at Fasilkom UI consists of lecturers with active research topics in machine learning, computer vision, and image processing topics. The MLCV lab is lead by a head and a director.

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: dir" %}
{% include list.html data="members" component="portrait" filters="role: researcher" %}


{% include section.html background="images/background.jpg" dark=true %}

 The members also include the current students conducting research under the lecturers.

{% include section.html %}

{% capture content %}

<!--{% include list.html data="members" component="portrait" filters="role: student" %}-->

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
