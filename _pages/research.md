---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "profile.png"
---

My research centers on two main scientific areas:

First, advanced manufacturing of nano-/micro-electromechanical systems (NEMS/MEMS) is a focus during my Ph.D..
My microfabrication training in supercleanroom lies in using and mastering lithography, dry etching, metal 
deposition, the sample inspection and metrology.

Second, theoretical modelling of nanoelectromechanics is another key. My goals are to analyse and calculate 
the motion equations of capacitively coupled mechanical resonators. With the calculations, mechanical
resonators provide rich opportunities for ultrasensitive detection of tiny forces or Brownian motions.

Previously, my aim was to use magnetic-/electric-field to study the interaction between light and two dimensional liquid crystals (LCs), such as hexagonal boron nitride.

In other early explorations, carbon nanotubes (CNTs) and graphene (e.g., with electrical, optical and mechanical natures) were used as enhancement agents.


<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
