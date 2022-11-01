---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "profile.png"
---

My academic research centers on two main scientific areas:

First, advanced manufacturing of nano-/micro-electromechanical systems (NEMS/MEMS) is a focus during my Ph.D..
My microfabrication training in cleanroom aims for practicing and understanding lithography, dry etching, metal 
deposition as well as the sample inspection and metrology.

Second, theory calculations of cavity optomechanics is another key. My goals are to calculate and analyse the basis of the equations 
of motion of mechanical resonators in capacitive coupling schemes. With the calculatons, mechanical resonators provide a lot of opportunities for 
quantum engineering, different resonators entangling, and ultrasensitive detection of tiny forces or masses.

Prior to doing the above, my major target was to tune the propagation of polarized lights through magnetically or electrically controlling two dimensional
liquid crystals (LCs), such as hexagonal boron nitride.

In other respects, the use of nanomaterials including carbon nanotubes (CNTs) and graphene or more was my early exploration.


<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
