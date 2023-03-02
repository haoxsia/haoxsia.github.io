---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "profile.png"
---

He/His research now contains two main scientific areas:

First, <ins>advanced manufacturing of nano-/micro-electromechanical systems (NEMS/MEMS)</ins> is fundamental during his Ph.D.. Achieving high-Q factor of NEMS/MEMS devices is critical, because it plays an important role in squeezing mechanical-mode-based quantum ground state in order to enhance measurement sensitivity. Here, his microfabrication training in supercleanroom focuses on using EB lithography, dry etching and metal evaporation processes to fabricate high-Q nano-/micro-resonant capacitor devices, followed by sample inspection and metrology (at room temperature).

Second, <ins>theory modeling and simulation of NEMS/MEMS devices</ins> are key. Based on cavity-enhanced effect, radiation pressure from the cavity enables strong coupling between optical(microwave) mode and mechanical mode, thereby utilizing this coupling to cool the mechanical mode down to quantum ground state. The cooled mechanical mode allows researchers to measure mechanical motion in quantum regime. Here, his goals are to analyse probe/pump spectrum operation and calculate 
the motion equations of a mechanical system based on capacitive scheme. With the manipulation, calculations and simulations, the mechanical system offers promising avenues to ultrasensitive detection for mass, force, and (Brownian) motion. It could enable ground state cooling and quantum entanglement further.

Previously (2 years ago), he focused on liquid crystals (LCs) based micro-/nano-photonic devices. His aim was to use magnetic-/electric-field to investigate the light-matter interaction between polarized lights and two dimensional LCs, such as hexagonal boron nitride, thereby studying the underlying physical phenomena and applications.

In other very early (5 years ago) explorations, carbon nanotubes (CNTs) and graphene (e.g., with optical, electrical and mechanical natures) were investigated for optoelectronics applications and more.


<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
