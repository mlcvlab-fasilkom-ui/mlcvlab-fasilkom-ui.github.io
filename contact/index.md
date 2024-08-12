---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Our lab is located at Gedung/Building A, Fakultas Ilmu Komputer, Kampus UI Depok, Depok, Jawa Barat, Indonesia, 16424. Feel free to contact one of our researchers for collaborations.

{%
  include button.html
  type="email"
  text="mlcvlab@cs.ui.ac.id"
  link="mlcvlab@cs.ui.ac.id"
%}

{% include button.html type="address" tooltip="Our location on Google Maps for easy navigation" link="https://www.google.com/maps/dir//fasilkom+ui/@-6.363975,106.8277362,18z/data=!4m9!4m8!1m1!4e2!1m5!1m1!1s0x2e69ec1ad14fb6cf:0xc94e4d829420fa15!2m2!1d106.8286886!2d-6.3646009?hl=en" %}

{% include button.html type="website" text="CS.UI" tooltip="Faculty of Computer Science, Universitas Indonesia" link="https://cs.ui.ac.id/" %}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/Projects.jpg"
  caption="Projects in MLCV Lab"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/Topics.jpg"
  caption="Research Topics in MLCV Lab"
%}

{% endcapture %}

<!--
{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Machine Learning and  
Computer Vision
{% endcapture %}

{% capture col2 %}
(MLCV) Lab
{% endcapture %}

{% capture col3 %}
Faculty of Computer Science
2024
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
-->
