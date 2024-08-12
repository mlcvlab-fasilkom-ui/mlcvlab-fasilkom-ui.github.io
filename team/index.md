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



{% include section.html %}

<!--{% capture content %}

{% include list.html data="members" component="portrait" filters="role: student" %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}-->
{% capture col1 %}

{%
  include figure.html
  image="images/SIBIapp.jpg"
  caption="Text-to-Gesture SIBI"
  link="https://www.google.com/maps/dir//fasilkom+ui/@-6.363975,106.8277362,18z/data=!4m9!4m8!1m1!4e2!1m5!1m1!1s0x2e69ec1ad14fb6cf:0xc94e4d829420fa15!2m2!1d106.8286886!2d-6.3646009?hl=en"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/Topics.jpg"
  caption="Research Topics in MLCV Lab"
%}

{% endcapture %}

{% include grid.html style="square" content=content %}
