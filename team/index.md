---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Our team is composed of a mosaic of scientists, each of which brings different expertise and points of view. Our group strives to create a safe space for all members, no matter the position or role. We advocate for freedom of expression (avoiding interpersonal conflicts) and open communication where members feel confident to offer their ideas and questions. To benefit from our different backgrouns, everyone must feel heard and involved in the discussions. 

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html dark=true %}

Our work is largely collaborative, and we work with a wide range of groups from around the world. We're always on the lookout for new and unique perspectives.
We want to push the frontier of data science and train the next generation of data scientists.

{%
  include button.html
  icon="fa-solid fa-handshake-angle"
  text="Join the Team"
  link="join"
  style="button"
%}

{% include section.html %}

## Funding

{% capture content %}
{% include figure.html image="images/team/ssmf-logo-head.png" caption="Swedish Society for Medical Research - Svenska Sällskapet för Medicinsk Forskning" link="https://www.ssmf.se/" width="100%" %}  
{% include figure.html image="images/team/logotyp_VR.png" caption="Swedish Research Council" link="https://www.vr.se/" width="100%" %}  
{% include figure.html image="images/team/alf.png" caption="ALF-Agreement" link="https://www.alfvastragotaland.se/" width="100%" %}  


{% endcapture %}  
{% include grid.html content=content %}  

