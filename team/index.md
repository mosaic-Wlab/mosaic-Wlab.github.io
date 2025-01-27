---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Our team is composed of a mosaic of scientists, each of which brings different expertise and points of view. Our group strives to create a safe space for all members, no matter the position or role. We advocate for freedom of expression (avoiding interpersonal conflicts) and open communication where members feel confident to offer their ideas and questions. To benefit from our different backgrouns, everyone must feel heard and involved in the discussions. 

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

## Funding

{% capture content %}

[![Swedish Society for Medical Research - Svenska Sällskapet för Medicinsk Forskning](/images/team/ssmf-logo-head.svg)](https://www.ssmf.se/)  

[![Swedish Research Council - Vetenskapsrådet](/images/team/logotyp_vetenskapsrådet_liggande_sv.svg)](https://www.vr.se/)  

[![ALF-Agreement concerning research and education of doctors](/images/team/alf.png)](https://www.alfvastragotaland.se/)  

{% endcapture %}


