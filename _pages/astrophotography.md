---
layout: archive
title: "Astrophotography"
permalink: /astrophotography/
author_profile: true
---
<br>

My journey in astronomy started with the binocular telescope I had. Then my telescope became a small Newtonian telescope with a digital camera and a webcam behind it. Before I had a chance to study astronomy at university, I was already an amateur astronomer. Since then, I had used various telescopes from ground-based to space-based, from 0.4 m to 65 m in diameter, and from a single minor to the telescope array.

This page collects my astrophotographs taken in my journey.
<br>
{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}
<!-- {% assign ordered_pages = site.research %} -->
{% for post in ordered_pages %}

  {% include archive-single.html type="grid" %}

{% endfor %}

