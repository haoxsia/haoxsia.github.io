---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "profile.png"
---

My academic research focuses on two main areas:

First, advanced manufacturing of nano-/micro-electromechanical systems (NEMS/MEMS) is a focus during my Ph.D..
My microfabrication training in cleanroom relates to practicing and understanding lithography, dry ecthing, metal 
deposition as well as the sample inspection and metrology.

Second, theory developing of cavity optomechanics is another key. My tasks are in calculating and analysing the basis of the equations 
of motion of mechanical resonators in capacitive coupling schemes. Advances in mechanical resonators provide a lot of opportunities 
for quantum ground cooling, entangling different resonators, and ultrasensitive detection of tiny forces or masses. The measurement 
evaluation and experimentation for such resonator schemes are included before, during and after projects running.

Prior to doing above, tuning the propagation of polarized lights through magnetically or electrically controlling
two dimensional liquid crystals (LCs), such as hexagonal boron nitride, was my major target.

In other respects, the use of nanomaterials including carbon nanotubes and graphene or more was my early exploration.


<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
