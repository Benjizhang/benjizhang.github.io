---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "research/research3.png"
---

My academic research falls into three main areas.

<img src='/images/research/research3.png'>

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
