---
title: Team
nav:
  order: 4
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

We are an international team located in [Bergen, Norway](https://en.wikipedia.org/wiki/Bergen). We are affilitated with the [University of Bergen](www.uib.no) and the [Norwegian Institute of Public Health](fhi.no).

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role == 'researcher'" %}
{% include list.html data="members" component="portrait" filter="role == 'postdoc'" %}
{% include list.html data="members" component="portrait" filter="role == 'phd'" %}
{% include list.html data="members" component="portrait" filter="role == 'bioinformatician'" %}
{% include list.html data="members" component="portrait" filter="role == 'student'" %}
---

# {% include icon.html icon="fa-solid fa-users" %}Alumni

Over the years, we have had the pleasure to welcome many talented members. Here are some of our alumni.

{% include list.html data="members" component="portrait" filter="role == 'alumni'" %}

{% include section.html background="images/background.jpg" dark=true %}

Some pictures of the team in action.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/Team.jpg" %}
{% include figure.html image="images/team/presentation_1.jpg" %}
{% include figure.html image="images/team/presentation_2.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
