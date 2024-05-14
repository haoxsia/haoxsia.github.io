---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "profile.png"
---

He/His research centers on two main areas:

<ins>Nanofabrication for MEMS/NEMS</ins>. High-Q MEMS devices present their promising roles played by potential applications, such as force or mass sensors and quantum engineering. In the cleanroom, his fabrication method mainly focuses on using EB lithography and dry etching processes to fabricate high-Q devices, following with sample check and characterization (at room temperature).

<ins>Theory modeling and numerical simulating</ins>. With the help of cavity-enhanced sensing, the radiation pressure from light(microwave) circulating in one cavity enables optomechanical coupling between optical(microwave) mode and mechanical mode, thus allowing for sideband manipulating the displacement of the mechanical mode. His aim is to analyse a mode coupling nanoelectromechanical system while probe/pump multifrequency operating. This scheme offers a new opportunity for phonon based coupling optomechanics.

Previously (2 years ago), he worked on liquid crystals (LCs) nanophotonic devices. His aim was to study on the light-matter interaction between polarized lights and two-dimensional material LCs due to magnetic/electric-field flux control, thus exploring the physical phenomena and applications.

Very early (5 years ago), carbon nanotube and graphene (e.g., with optical, electrical and mechanical natures) have been investigated for optoelectronic applications.


<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
