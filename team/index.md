---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %}

## AISL Director
{% include list.html data="members" component="portrait" filter="role == 'Director'" %}

## Research Staff
{% include list.html data="members" component="portrait" filter="role == 'Research'" %}

## Master Students
{% include list.html data="members" component="portrait" filter="role == 'Master'" %}

## Undergraduage Students
{% include list.html data="members" component="portrait" filter="role == 'Bachelor'" %}

## Alumni
{% include list.html data="members" component="portrait" filter="role == 'Alumni'" %}

{% include section.html background="images/background.jpg" dark=true %}

<!-- Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %} -->