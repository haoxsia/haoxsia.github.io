---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "profile.png"
---

He/His research now centers on two main scientific areas:

First, <ins>advanced manufacturing for nano-/micro-electromechanical systems (NEMS/MEMS)</ins> is fundamental during his Ph.D.. Achieving high-Q NEMS/MEMS devices is critical, because it plays an important role in squeezing mechanical mode so as to enhance measurement sensitivity. In the cleanroom, his ultraclean fabrication training focuses on using EB lithography, dry etching and metal evaporation processes to fabricate high-Q micro/nano-devices, following with sample inspection and metrology (at room temperature).

Second, <ins>theory modeling and simulation for NEMS/MEMS devices</ins> are key. Based on cavity-enhanced displacement sensing effect, the radiation pressure from light(microwave) circulating in the cavity enables strong optomechanical coupling between optical(microwave) mode and mechanical mode, thus utilizing this coupling feature to sideband cool the mechanical mode. The cooled mechanical mode allows researchers to measure mechanical motion in classical or quantum regime. Now, his goals are to analyse probe/pump spectrum operation and calculate the motion equations of a mechanical system based on capacitive coupling scheme. By manipulating, calculating as well as simulating, the mechanical system offers very interesting opportunities for ultrasensitive detection for "ng" mass, "zN" force, and "pm" motion. The mechanical system could enable ground state cooling and quantum entanglement further.

Previously (2 years ago), he focused on liquid crystals (LCs) based micro-/nano-photonic devices. His aim was to use magnetic-/electric-field to investigate the light-matter interaction between polarized lights and two dimensional LCs, such as hexagonal boron nitride, thereby studying the underlying physical phenomena and applications.

In other very early (5 years ago) explorations, carbon nanotubes (CNTs) and graphene (e.g., with optical, electrical and mechanical natures) were investigated for optoelectronics applications and more.


<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
