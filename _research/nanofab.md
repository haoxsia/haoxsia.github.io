---
title: "Nanofabrication"
layout: single-portfolio
excerpt: "<img src='/images/research/2022-10-31-nanofab.png' alt=''>"
collection: research
order_number: 20
gallery:
  - url: https://haoxsia.github.io/images/research/2021-06-16-SiN-drum-etch.png
    image_path: https://haoxsia.github.io/images/research/2021-06-16-SiN-drum-etch.png
    alt: "Silicon nitride drum membrane release"
    title: "Silicon nitride drum membrane release"
  - url: https://haoxsia.github.io/images/research/2021-06-16-SiN-drum-bottom.png
    image_path: https://haoxsia.github.io/images/research/2021-06-16-SiN-drum-bottom.png
    alt: "Thin Aluminum layer deposition on the drum"
    title: "Thin Aluminum layer deposition on the drum"
  - url: https://haoxsia.github.io/images/research/2021-06-16-SiN-drum-gate.png
    image_path: https://haoxsia.github.io/images/research/2021-06-16-SiN-drum-gate.png
    alt: "Thick Aluminum layer deposition as the drum's top gate"
    title: "Thick Aluminum layer deposition as the drum's top gate"
header: 
  og_image: "https://haoxsia.github.io/images/research/2022-10-31-nanofab.png"
---

Outline (this page shortly introduces our development of the device, see our paper [here](https://pubs.acs.org/doi/10.1021/acs.nanolett.1c01477)):

1. Short introduction
2. Device fabrication
3. Device images gallery

## Preface

With the development of microelectronics and semiconductor industry, nano-/micro-manufacturing technologies have attracted increasing attention in nano/microscale devices, such as breath/blood pressure sensors in health monitoring [^1], microfluidics [^2] in biological analysis, accelerators [^3] and gyroscopes [^4] in mobile phones, and RF components [^5] in modern industry. With these aims, nano-/micro-electromechanical systems (NEMS/MEMS) are promising ideals to be applied in microelectronic integrations, thanks to their nano/microscales and physical properties control. By 2022, there will still be a huge market for MEMS products of about $20B in the world. Today, silicon nitride (SiN) mechanical resonators with high mechanical properties (e.g., tensile stress) are promising devices for fundamental research and applications. To achieve high quality factor while enabling electromechanical strong coupling in electrical integrated circuits, here we present developing silicon nitride mechanical resonator.


## Device fabrication

<p align="center">
  <img src="https://haoxsia.github.io/images/research/2021-06-16-SiN-drum-nanofab.png?raw=true" alt="Photo" style="width: 475px;"/> 
</p>

**Figs.(a-g)** show the fabrication process of silicon nitride drum mechanical resonators. We define the diameter of the drum by using electron beam (EB) resist CSAR62 to pattern circularly symmetric holes. The drum is released from the Si substrate by reactive ion etching (RIE) of the SiN layer ( $SF_{6}$ : Ar = 10 sccm : 10 sccm, for 6.5 min) through these opened holes, followed by a selective $XeF_{2}$ silicon etching. These holes occupy about 40 % ~ 45 % of the SiN drum area. Its suspended top-gate is fabricated by using EB resist PMMA as a top-gate support through soft-bake at the temperature of 140 $^{\circ}C$ and reflowed at 180 $^{\circ}C$. Then, we deposit the second layer EB resist MMA (methyl methacrylate) on the top of the support resist and pattern the gate structure. For the metal depositions, we first perform Ar ion etching process to clean the sample and then use with electron beam evaporation to deposition the thin films. All bonding pads on the chip are designed to be 50 Ohm impedance for microwave signals.

## Device images gallery

{% include gallery %}

SEM micrographs of the fabricated mechanical resonators were taken in the cleanroom: **Fig.(h)** Silicon nitride drum membrane released from the Si substrate; **Fig.(i)** Thin Al layer deposited on the released SiN drum membrane; **Fig.(j)** Thick Al layer as the drum's top gate, forming a capacitive coupling resonator.

------

[^1]: Ruth, Sara Rachel Arussy, Vivian Rachel Feig, Helen Tran, and Zhenan Bao. "Microengineering pressure sensor active layers for improved performance." Advanced Functional Materials 30, no. 39 (2020): 2003491.
[^2]: Koh, Ahyeon, Daeshik Kang, Yeguang Xue, Seungmin Lee, Rafal M. Pielak, Jeonghyun Kim, Taehwan Hwang et al. "A soft, wearable microfluidic device for the capture, storage, and colorimetric sensing of sweat." Science translational medicine 8, no. 366 (2016): 366ra165-366ra165.
[^3]: Kononchuk, Rodion, Jizhe Cai, Fred Ellis, Ramathasan Thevamaran, and Tsampikos Kottos. "Exceptional-point-based accelerometers with enhanced signal-to-noise ratio." Nature 607, no. 7920 (2022): 697-702.
[^4]: Howell, John C., Merav Kahn, Einav Grynszpan, Ziv Roi Cohen, Stefania Residori, and Umberto Bortolozzo. "Doppler Gyroscopes: Frequency vs Phase Estimation." Physical Review Letters 129, no. 11 (2022): 113901.
[^5]: Sharaf, A., A. Nasr, A. M. Elshurafa, and M. Serry. "Design analysis and simulation of a digital RF MEMS varactor with high capacitive ratio." Microsystem Technologies 28, no. 8 (2022): 1831-1844.

