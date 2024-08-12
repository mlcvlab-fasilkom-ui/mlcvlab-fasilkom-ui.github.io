---
title: Member
nav:
  order: 1
  tooltip: Our lab members
---

# {% include icon.html icon="fa-solid fa-users" %}Member

The MLCV lab at Fasilkom UI consists of lecturers with active research interests in machine learning, computer vision, and image processing. It is led by a head of the lab and a director.

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: dir" %}
<br />
{% include list.html data="members" component="portrait" filters="role: researcher" %}


{% include section.html background="images/active_banner_720_15fps.gif" dark=true %}

For more information, please check each researcher's personal profile on the Fasilkom website, which is linked to each profile.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/SIBI_box.jpg" %}
{% include figure.html image="images/IQA_box.jpg" %}
{% include figure.html image="images/Stethosoul_box.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
