---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Table of contents| Selected publications 
--- | --- 
*Still* | `renders` 
1 | 2 
1 | 2 

Previously, my aim was to use magnetic-/electric-field to investigate the light-matter interaction between polarized lights and two dimensional liquid crystals (LCs), such as hexagonal boron nitride.

In other early explorations, carbon nanotubes (CNTs) and graphene (e.g., with optical, electrical and mechanical natures) were used as enhancement agents.


<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}

