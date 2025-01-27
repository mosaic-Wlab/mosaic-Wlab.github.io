---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

We are physically located at the [Wallenberg Laboratory](https://www.gu.se/en/wlab) in the beautiful city of Gothenbrug, Sweden.

{%
  include button.html
  type="email"
  text="pol.sole.navais@gu.se"
  link="pol.sole.navais@gu.se"
%}
{%
  include button.html
  type="phone"
  text="(+46) 031 342 29 29"
  link="46-031-342-29-29"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps/place/Bruna+str%C3%A5ket+16,+413+45+G%C3%B6teborg/@57.6815364,11.958416,17z/data=!3m1!4b1!4m6!3m5!1s0x464ff3101270a299:0x5873060b6d10602e!8m2!3d57.6815364!4d11.9609909!16s%2Fg%2F11c239c3yt?entry=ttu&g_ep=EgoyMDI1MDEyMi4wIKXMDSoASAFQAw%3D%3D"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
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
