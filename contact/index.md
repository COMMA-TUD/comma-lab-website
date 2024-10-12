---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Our lab is part of the [Faculty of Aerospace Engineering](https://www.tudelft.nl/en/ae) at the [Delft University of Technology (TU Delft)](https://www.tudelft.nl/en/). We are hosted within the [Department of Aerospace Structures and Materials](https://www.tudelft.nl/index.php?id=3842).

{%
  include button.html
  type="email"
  text="b.caglar@tudelft.nl"
  link="b.caglar@tudelft.nl"
%}
{%
  include button.html
  type="phone"
  text="+31 15 27 83566"
  link="+31 15 27 83566"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/q9adj9ry5ZFcm4Ag8"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/contact/aerial_ae_faculty.jpg"
  caption="TUDelft, [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0)"
  link="https://www.tudelft.nl/en/ae"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/contact/autumn_in_delft.jpg"
  caption="[Autumn in Delft](https://www.deviantart.com/siddhartha19/art/Autumn-in-Delft-333968210), [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0)"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
