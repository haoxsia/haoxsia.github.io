---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "profile.png"
---

My research centers on two main scientific areas:

First, <ins>advanced manufacturing of nano-/micro-electromechanical systems (NEMS/MEMS)</ins> is a foundation during my Ph.D..
My microfabrication training in supercleanroom focuses on using EB lithography, dry etching and metal evaporation processes to fabricate nano-/micro-resonant capacitor devices, followed by sample inspection and metrology.

Second, <ins>theory modeling and simulation of NEMS/MEMS devices</ins> are other keys. My goals are to analyse and calculate 
the motion equations of a mechanical system consisting of capacitively coupled distinct mechanical resonators. With the calculations and simulations, the mechanical system offers rich application opportunities for ultrasensitive detection for mass, force, and (Brownian) motion. It can be potentially extended to quantum engineering domain for ground state cooling and quantum states entanglement.

Previously, I focused on liquid crystals (LCs) based micro-/nano-photonic devices. My aim was to use magnetic-/electric-field to investigate the light-matter interaction between polarized lights and two dimensional LCs, such as hexagonal boron nitride, thereby studying the underlying physical phenomena and their applications.

In other early explorations, carbon nanotubes (CNTs) and graphene (e.g., with optical, electrical and mechanical natures) were investigated for optoelectronics applications and more.


<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
