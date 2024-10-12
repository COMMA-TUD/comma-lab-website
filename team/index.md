---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Our team consists of highly motivated researchers driven by the ambition to advance the field of composite materials and contribute meaningfully to scientific research and practical, real-world applications. 

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: postdoc" %}
{% include list.html data="members" component="portrait" filters="role: phd" %}

{% include section.html background="images/background.jpg" dark=true %}

Collaborative work is at the heart of our DNA. By partnering with leading institutes and applying cutting-edge technologies, we strive to make a lasting impact in academia and industry. 

Are you interested in joining us? See our open position and available master thesis topics.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
