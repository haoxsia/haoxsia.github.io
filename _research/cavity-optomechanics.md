---
title: "Cavity optomechanics"
layout: single-portfolio
excerpt: "<img src='/images/research/2022-10-31-theory.png' alt=''>"
collection: research
order_number: 30
header: 
  og_image: "https://haoxsia.github.io/images/research/2022-10-31-theory.png"
---

> Outline (this page is a minimal version of our paper [here](https://pubs.acs.org/doi/10.1021/acs.nanolett.2c01848?ref=pdf)):
> * Schematic of coupling two distinct mechanical resonators
> * Strategy of spectrum operation of red/blue sideband pumping schemes
> * Electromechanically induced transparecy and amplification

<p align="center">
  <img src="https://haoxsia.github.io/images/research/2022-09-09-phonon-cavity-TOC.png?raw=true" alt="Photo" style="width: 600px;"/> 
</p>

Nano-/micro-electromechanical systems (NEMS/MEMS) that allow mechanical degrees of freedom (e.g. displacement) to couple with electrical signals are promising devices for fundamental research, in particular for sensing tiny mass [^1], force [^2] and motion [^3]. Recent examples have implemented the nonlinearity or mechanical transduction design to realize logic gates [^4] or RF amplifiers [^5]. Nowadays, the phonon-cavity schemes existed in optomechanics have been proposed for investigating electromechanical coupling. Similar to light-matter interaction in the optical domain, optomechanics consisting of "mechanical" phonons coupled to "microwave" cavity phonons enables phenomena of "phonon" interferences. In very recent years, two different individual mechanical resonators in capacitively coupled schemes have been built for observing their entanglement [^6]. The multimode optomechanical sensing in single mechanical resonator has also been created for sensing a single nanoparticle [^7]. For these reasons, the establishment of the coupling between different resonators with compact structures is still promising.

## Schematic of coupling two distinct mechanical resonators

<p align="center">
  <img src="https://haoxsia.github.io/images/research/2022-09-09-phonon-cavity-schematic.png?raw=true" alt="Photo" style="width: 600px;"/> 
</p>

> Here, we present coherent energy transfers between two capacitively coupled and distinct mechanical resonators. As **Fig.(a)** shows, the two mechanical resonators embedded in the electrical integrated circuits can be independently driven by the signals from RF1 and RF2. At the same moment, they can also be independently detected with probed and reflected signals from microwave source. **Fig.(b)** shows the cross-sectional view of the mechanical resonator consisting of a SiN drum membrane coupled to a suspended Al drum membrane. In this work, we did nanofabrication of the SiN drum membrane with 80nm thickness and 36um diameter, and the Al drum membrane with 550nm thickness and 40um diameter (see [nanofab](https://haoxsia.github.io/research/nanofab/)). **Fig.(c)** demonstrates the linear resonance responses of the Al drum and SiN drum resonators, showing the Al drum with a low frequency of 2.95 MHz and the SiN drum with a high frequency of 11.79 MHz. We therefore investigate such two mechanical resonators by using the mechanical mode (the SiN drum) with higher resonance frequency $Ω_{1}$ as a phonon cavity and pumping this cavity with a signal with frequency difference $∼Ω_{1} ± Ω_{2}$, also so called red/blue sidebands, where $Ω_{2}$ is the low resonance frequency from the other mode (the Al drum).

## Strategy of spectrum operation of red/blue sideband pumping schemes

<p align="center">
  <img src="https://haoxsia.github.io/images/research/2022-09-09-spectrum-operation-probe-SiN-1.png?raw=true" alt="Photo" style="width: 600px;"/> 
</p>

> When probing the phonon cavity (the SiN drum), we present our strategy of spectrum operation of red/blue sidebands. In this two-tone scheme, the electromechanical interactions between two coupled mechanical resonators, in parallel to the light-matter interaction in the optical domain, can be decomposed into two coherent processes in order to describe the transfers of energy in the form of phonons. **Fig.(a)** shows that the probe and pump tones create a phonon cavity force acting on the unprobed Al drum that excites the mechanical vibrations, marked by red arrow curve. At the same moment, these created mechanical phonons are fed back to the probed SiN drum resonator, marked by grey in the inverse process. Therefore, an interference is built between these phonons acting on the unprobed Al drum (related to the term $n_{p}g_{0}^2χ_{2}$) and initial probed phonons (related to the term $χ_{1}$). This interference phenomena can be either destructive or constructive depending on the phonon cavity (the SiN drum) pumped at red/blue sidebands. **Fig.(b)** shows the probed signal suppressed fully when the phonon cavity at red sideband pumping, and the probed signal getting a larger amplification when the phonon cavity at blue sideband pumping. 


<p align="center">
  <img src="https://haoxsia.github.io/images/research/2022-09-09-spectrum-operation-probe-Al-1.png?raw=true" alt="Photo" style="width: 600px;"/> 
</p>

> When probing the Al drum, **Fig.(a)** shows that the probe and pump tones create a phonon cavity force acting on the unprobed SiN drum, marked by red arrow curve. At the same moment, these created mechanical phonons are fed back to the probed Al drum resonator, marked by grey in the inverse process. An interference therefore is built between these phonons acting on the unprobed SiN drum (related to the term $n_{p}g_{0}^2χ_{1}$ or $n_{p}g_{0}^2χ_{1}^* $) and initial probed phonons (related to the term $χ_{2}$). It is worth to note in our case the phonon cavity damping rate is two orders of magnitude smaller than that of the coupled Al drum. As known in the motion equation with a probe signal of the coupled Al drum, the damping rate of the unprobed SiN drum (related to the term $n_{p}g_{0}^2χ_{1}$ or $n_{p}g_{0}^2χ_{1}^* $) determines the frequency bandwidth of the transparency or amplification effects. **Fig.(b)** shows the Lorentzian curve of the mechanical response of the probed Al drum exhibiting a narrow dip inside the bandwidth of the transparency window due to $γ_{SiN}<γ_{Al}$. This phenomenon is observed for investigating the control of the transparency and amplification by means of engineering the mechanical damping rate in the phonon-cavity optomechanical system.

## Electromechanically induced transparecy and amplification

<p align="center">
  <img src="https://haoxsia.github.io/images/research/2022-09-09-EI-T-A-probe-SiN-1.png?raw=true" alt="Photo" style="width: 600px;"/> 
</p>

> Through controlling the electromechanical energy transfers in the form of phonons, we experimentally demonstrate electomechanically induced transparency and amplification of the input signal so that the coupled system creates signal interferences. **Fig.(b,e)** shows that when probing the phonon cavity (the SiN drum), we measure the mechanical responses of the coupled drum resonators as a function of the pump tone detuning $Δ$ and the probe frequency detuning $δ$ at red/blue sideband pumping schemes. These measurements clearly indicate that the damping rate of the interference window corresponding to the pump tone detuning $Δ$ is related to the unprobed Al drum. Here, the unprobed Al drum can be as a phonon transfer station. Within the bandwidth of the unprobed Al drum resonator, phonons can be generated due to the interaction between probe and pump tone, and can coherently create destructive in **Fig.(b)** or constructive in **Fig.(e)** interferences with the probe tone.

<p align="center">
  <img src="https://haoxsia.github.io/images/research/2022-09-09-EI-coupling-probe-SiN-1.png?raw=true" alt="Photo" style="width: 600px;"/> 
</p>

> When still probing the phonon cavity (the SiN drum), we simultaneously measure the electromechanical responses of the probed SiN and unprobed Al drums at blue sideband pumping scheme. **Fig.(c)** clearly demonstrates a constructive interference when the probed signal is amplified within the interference window. Simultaneously, **Fig.(e)** indicates phonon generation detected in the mechanical mode of the unprobed Al drum resonator. This phenomenon manifests the electromechanical coupling between two drums “dancing” at the same time.

<p align="center">
  <img src="https://haoxsia.github.io/images/research/2022-09-09-EIT-probe-Al-1.png?raw=true" alt="Photo" style="width: 600px;"/> 
</p>

> When probing the Al drum, **Fig.(b)** shows a destructive interference of the mechanical response of the probed Al drum. It is worth to notice that at a red sideband pumping the measurement results in **Fig.(b)** feature splitting within the transparency window due to the $γ_{SiN}<γ_{Al}$. This is because the damping rate of the unprobed SiN drum (related to the term $n_{p}g_{0}^2χ_{1}$) determines the frequency bandwidth of the transparency effect of the Al drum.

In brief, the basics of motions of the capacitively coupled SiN and Al drum resonators have been demonstrated, including nanofabrication of the device structure, the strategy of spectrum operation of red/blue sidebands and the electromechanically induced transparency/amplifications. More details see our paper [here](https://pubs.acs.org/doi/10.1021/acs.nanolett.2c01848?ref=pdf)



------

[^1]: Yuksel, Mert, Ezgi Orhan, Cenk Yanik, Atakan B. Ari, Alper Demir, and M. Selim Hanay. "Nonlinear nanomechanical mass spectrometry at the single-nanoparticle level." Nano letters 19, no. 6 (2019): 3583-3589.
[^2]: Mamin, H. J., and D. Rugar. "Sub-attonewton force detection at millikelvin temperatures." Applied Physics Letters 79, no. 20 (2001): 3358-3360.
[^3]: Teufel, John D., Tobias Donner, M. A. Castellanos-Beltran, Jennifer W. Harlow, and Konrad W. Lehnert. "Nanomechanical motion measured with an imprecision below that at the standard quantum limit." Nature nanotechnology 4, no. 12 (2009): 820-823.
[^4]: Guerra, Diego N., Adi R. Bulsara, William L. Ditto, Sudeshna Sinha, K. Murali, and P. Mohanty. "A noise-assisted reprogrammable nanomechanical logic gate." Nano letters 10, no. 4 (2010): 1168-1171.
[^5]: Karabalin, R. B., Ron Lifshitz, M. C. Cross, M. H. Matheny, S. C. Masmanidis, and M. L. Roukes. "Signal amplification by sensitive control of bifurcation topology." Physical review letters 106, no. 9 (2011): 094102.
[^6]: Kotler, Shlomi, Gabriel A. Peterson, Ezad Shojaee, Florent Lecocq, Katarina Cicak, Alex Kwiatkowski, Shawn Geller et al. "Direct observation of deterministic macroscopic entanglement." Science 372, no. 6542 (2021): 622-625.
[^7]: Sbarra, Samantha, Louis Waquier, Stephan Suffit, Aristide Lemaître, and Ivan Favero. "Multimode optomechanical weighting of a single nanoparticle." Nano Letters 22, no. 2 (2022): 710-715.

