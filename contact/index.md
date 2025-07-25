---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Questions, suggestions? Don't hesitate to contact Marc.

{%
  include button.html
  type="email"
  text="marc.vaudel@uib.no"
  link="marc.vaudel@uib.no"
%}
{%
  include button.html
  type="website"
  text="Webpage"
  link="https://www4.uib.no/en/find-employees/Marc.Vaudel"
%}
{%
  include button.html
  type="address"
  tooltip="Our location"
  link="https://osm.org/go/0RvzUV5IS?layers=N&m="
%}

{% include section.html dark=true %}

{% capture col1 %}
### Visitor address

    Barne- og ungdomsklinikken, glasblokkene, blokk1 Helse Bergen HF, Haukeland universitetssjukehus
    Room 6141, 6th floor
    5021 Bergen 
    Norway
{% endcapture %}

{% capture col2 %}
### Postal address

    P.O. Box 7804
    NO-5020 Bergen
    Norway
{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}
