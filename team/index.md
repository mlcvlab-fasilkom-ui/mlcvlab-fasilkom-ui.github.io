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
<br />
{% include list.html data="members" component="portrait" filters="role: researcher" %}


{% include section.html background="images/background.jpg" dark=true %}

For more information please check each researcher's personal profile at Fasilkom website which are linked in each profile.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/SIBI_box.jpg" %}
{% include figure.html image="images/IQA_box.jpg" %}
{% include figure.html image="images/Stethosoul_box.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
