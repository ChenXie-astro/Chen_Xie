---
layout: archive
title: "Astrophotography"
permalink: /astrophotography/
author_profile: true
---





My journey of astronomy started with the binocular telescope I had. And then it became a small Newtonian telescope with a DSLR and a webcam behind it. Before I had a chance to study astronomy in the University, I was already an amerture atronmer. Since then, I had reed various telecopes from ground-based to space-based, from 0.4 m to 65 m in diameter, and from single minor to interformer.

This page collects my astrophotographs taken in my journey.

<br>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}
<!-- {% assign ordered_pages = site.research %} -->
{% for post in ordered_pages %}

  {% include archive-single.html type="grid" %}

{% endfor %}

