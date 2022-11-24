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
My microfabrication training in cleanroom aims for practicing and understanding lithography, dry etching, metal 
deposition, the sample inspection and metrology.

Second, theoretical analysis of nanoelectromechanics is another key. My goals are to calculate and analyse the basis of the equations 
of motion of mechanical resonators in capacitive coupling schemes. With the calculations, mechanical resonators provide a lot of opportunities for 
quantum engineering, different resonators entangling, and ultrasensitive detection of tiny forces or motions.

Prior to doing the above, my major target was to tune the propagation of polarized lights through magnetically or electrically stimulating the alignment of two dimensional liquid crystals (LCs), such as hexagonal boron nitride.

In other early explorations, carbon nanotubes (CNTs) or more nanomaterials (e.g., with electrical, optical and mechanical natures) were used as enhancement agents.


<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
