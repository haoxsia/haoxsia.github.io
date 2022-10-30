---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "profile.png"
---

My academic research focuses on two main areas:
First, advanced manufacturing of nano-/micro-electromechanical systems (NEMS/MEMS)
is an important point during my doctoral studies, among which I also need to receive
a professional training in cleanroom and learn laboratory rules. More important, my
microfabrication training relates to practicing and understanding lithography, dry
ecthing, metal deposition as well as the sample inspection and metrology.

Second, theory developing of cavity optomechanics physics is another important key,
in which mainly in the microwave domain I calculate and analyse the basis of equations
of motion of mechanical resonators. Advances in mechanical resonators provide a lot
of opportunities to do quantum ground cooling, entangling different resonators, and
ultrasensitive detection for tiny forces or masses. Of course, the measurement evaluation
and experiments for these kinds of resonator's schemes are included before, during and after
projects running.

Prior to doing above, magnetically and electrically controlling two dimensional liquid
crystals (LCs) for tuning polarized lights propragation are my major targets.

In others, nanomaterials including carbon nanotubes and graphene are my early explores.


<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
