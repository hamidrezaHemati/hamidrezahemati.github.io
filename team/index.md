---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Our laboratory consists of a collaborative group of researchers, graduate students, and undergraduate trainees working together under the guidance of Professor Mahdi Javanmardi. Each member contributes uniquely to our shared mission of scientific exploration and innovation. We foster an environment that values curiosity, critical thinking, and mutual support.
Explore the team below to learn more about the people behind our work.

{% include section.html %}

<div style="text-align: center">
  <h2>AISL Director</h2>
</div>
{% include list.html data="members" component="portrait" filter="role == 'Director'" %}

<div style="text-align: center">
  <h2>Research Staff</h2>
</div
{% include list.html data="members" component="portrait" filter="role == 'Research'" %}

<div style="text-align: center">
  <h2>M.Sc. Students</h2>
</div>
{% include list.html data="members" component="portrait" filter="role == 'Master'" %}

<div style="text-align: center">
  <h2>Undergraduate Students</h2>
</div>
{% include list.html data="members" component="portrait" filter="role == 'Bachelor'" %}

<div style="text-align: center">
  <h2>Alumni</h2>
</div>
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