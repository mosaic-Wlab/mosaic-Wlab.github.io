---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

We are physically located at the (Wallenberg Laboratory)[https://www.gu.se/en/wlab] in the beautiful city of Gothenbrug, Sweden.

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
  link="[https://www.google.com/maps](https://www.google.com/maps/place/Brown+Passage+16+Parking/@57.6845086,11.9553609,16z/data=!4m10!1m2!2m1!1swallenberg+laboratory!3m6!1s0x464ff31011ece82f:0x9436004d4b23866!8m2!3d57.6811852!4d11.9609134!15sChV3YWxsZW5iZXJnIGxhYm9yYXRvcnmSAQtwYXJraW5nX2xvdOABAA!16s%2Fg%2F11f2gsjpwj?entry=ttu&g_ep=EgoyMDI1MDEyMi4wIKXMDSoASAFQAw%3D%3D)"
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
