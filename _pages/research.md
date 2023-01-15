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
My microfabrication training in supercleanroom lies in using and mastering lithography, dry etching, metal evaporation, sample inspection and metrology.

Second, theoretical modelling of nanoelectromechanics is another key. My goals are to analyse and calculate 
the motion equations of a mechanical system consisting of capacitively coupled two mechanical resonators. With the calculations, the mechanical system provides rich opportunities for ultrasensitive detection (about 10 $pm/ \sqrt{Hz}$) for tiny forces and Brownian motions.

Previously, my aim was to use magnetic-/electric-field to investigate the interaction between light and two dimensional liquid crystals (LCs), such as hexagonal boron nitride.

In other early explorations, carbon nanotubes (CNTs) and graphene (e.g., with optical, electrical and mechanical natures) were used as enhancement agents.


<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
