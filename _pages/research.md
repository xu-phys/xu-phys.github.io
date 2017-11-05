---
title: "Bin Xu's website - Research"
layout: textlay
excerpt: "Bin Xu's website -- Research"
sitemap: false
permalink: /research/
---

# Research

My research is in the field of computational solid state physics, using first-principles-based techniques such as density functional theory, effective Hamiltonian, and phenomenological method to study materials of fundamental and technological interests. I am interested in understanding and designing materials with intriguing properties and functionalities. Some of the publised works are highlighted below.

## Multiferroics

Multiferroics form an important class of materials that possess coupled long-range electric and magnetic orders. Such magneto-electric coupling is promising for designing new devices taking advantage of the control of magnetic properties by the application of an electric field; or vise versa.

<br><br>

![]({{ site.url }}{{ site.baseurl }}/images/respic/BNFO_PM_AFM.jpg){: style="width: 200px; float: right; border: 10px"}

The most studied multiferroic to date is bismuth ferrite (BiFeO3 or BFO) because it exhibits both ferroelectric and magnetic ordering well above room temperature. However, rare-earth-substituted BFO (BRFO) has improved or even novel multiferroic properties compared with BFO. In BRFO (R=Nd in [Adv. Funct. Mater. 25 552 (2015)](http://onlinelibrary.wiley.com/doi/10.1002/adfm.201403811/full)) disordered solid solution, an applied electric field can trigger a paramagnetic-to-antiferromagnetic transition in BNFO solid solutions, which is due to the strong magnetoelectric coupling in the vicinity of a critical point (triple point) where large variation of both magnetic and electric orders can be expected.

<br><br>
<br><br>

![]({{ site.url }}{{ site.baseurl }}/images/respic/hif_switch.jpg){: style="width: 400px; float: left; border: 10px"} 

In BRFO ordered 1/1 superlattice (hybrid improper ferroelectric), the direction of the weak ferromagnetization can be controlled by the an electric field applied perpendicular to the polarization direction. This is associated with two trilinear couplings connecting the polarization to the magnetic order, one being the trilinear coupling that leads to the hybrid improper ferroelelctricity, and the other is a Dzyaloshinskii-Moriya interaction ([Adv. Funct. Mater. 25 3626 (2015)](http://onlinelibrary.wiley.com/doi/10.1002/adfm.201501113/abstract)).

<br><br>
<br><br>
<br><br>
<br><br>

## Ferroelectrics and antiferroelectrics

![]({{ site.url }}{{ site.baseurl }}/images/respic/BFO_switch.jpg){: style="width: 500px; float: right; border: 10px"} 

The polarization switching mechanisms in intrinsic BFO is found to be homogeneous in the rhombohedral phase, for which the polarization is strongly coupled to oxygen octahedral tiltings. On the other hand, in the super-tetragonal phase the switching mechanism changes with increasing electric field, which can be explained by the field dependence of the switching barriers as well as the hierarchy of these barriers between different switching processes ([Phys. Rev. B 95, 104104(2017)](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.95.104104)).

<br><br>
<br><br>

![]({{ site.url }}{{ site.baseurl }}/images/respic/stdp.jpg){: style="width: 500px; float: left; border: 10px"} 

The inhomogeneous switching can lead to memristive behavior when it is used in ferroelectric tunnel junctions (FTJ). In the work of [Nat. Commun. 8, 14736 (2017)](https://www.nature.com/articles/ncomms14736) we report spike-timing-dependent plasticity (STDP) from BFO-based FTJs. The STDP behavior relies on the change of resistance states (memristor), which originates from the intrinsic inhomogeneous polarization switching. Unsupervised learning of pattern recognition is further demonstrated.

<br><br>
<br><br>

![]({{ site.url }}{{ site.baseurl }}/images/respic/BNFO_AFE.jpg){: style="width: 300px; float: right; border: 10px"} 

The BRFO system is antiferroelectric (AFE) with relatively large composition of rare earth, and it is predicted to be very promising for high-power energy storage ([Nat. Commun. 8 15682 (2017)](https://www.nature.com/articles/ncomms15682)). Because of its characteristic P-E curves, it is predicted to allow high energy densities (100-150 J/cm3) and efficiencies (80-88%) for electric fields that may be within the range of feasibility upon experimental advances (2-3 MV/cm). Additionally, a simple model is derived to describe the energy density and efficiency of a general antiferroelectric material, providing a framework to assess the effect on the storage properties of variations in doping, electric field magnitude and direction, epitaxial strain, temperature, etc., which can facilitate future search of antiferroelectric materials for energy storage.

<br><br>
<br><br>

## Thermoelectrics

Accurate prediction of transport properties from first-principles is desirable for thermoelectric applications. Combining the Boltzmann transport theory with the predictive power of density functional calculations, the electrical conductivity, Seebeck coefficient, electronic and lattice thermal conductivity can be computed within the diffusive transport regime.


![]({{ site.url }}{{ site.baseurl }}/images/respic/sbk_li.png){: style="width: 250px; float: right; border: 10px"} 

With the fully-first-principles approach based on electron-phonon interactions that implemented in the ABINIT package ([Comput. Phys. Commun. 205 106 (2016)](http://www.sciencedirect.com/science/article/pii/S0010465516300923)), the abnormal sign of Seebeck coefficient in lithium is explained ([Phys. Rev. Lett. 112 196603 (2014)](http://link.aps.org/doi/10.1103/PhysRevLett.112.196603)). Near the Fermi level, the scattering of electrons is found to be more than that of holes due to the significantly increasing density of states; on the other hand, the electron-phonon interaction is found to be less relevant, contrary to what has been believed for several decades. Band engineering combined with this mechanism may open the door to new “ambipolar” thermoelectric materials, with a tunable sign for the thermopower even if either n- or p-type doping is impossible.

<br><br>
<br><br>

## Code development

<!--
Our overarching goal is to explore and understand new quantum states of electronic matter on the atomic scale. To do so, we use and develop novel spectroscopic-imaging scanning tunneling microscopy (SI-STM) tools to visualize the relevant quantum mechanical degrees of freedom.

Questions of interest include: (i), How does the Mott state collapse upon doping and how is this related to the complex phase diagram of high-temperature superconductors? (ii), What is the strange metal phase seen in correlated electron systems? Is this an exotic long-range entangled state? What is the mechanism of dissipation in that state? (iii), Why is the transition temperature in high-temperature superconductors so high? 
 
![]({{ site.url }}{{ site.baseurl }}/images/respic/layers_real.jpg){: style="width: 300px; float: right; border: 10px"} 

Currently, our instrument of choice  is SI-STM.  State-of-the-art SI-STM measures an array of tunneling spectra on a given sample, registered to the atomic sites with picometer precision. Each is proportional to the local density of states at a given location. Ideally, the recorded spectra are so tightly packed that the measurement yields a three-dimensional mapping of the local density of states as a function of locations and energy. This is shown on the image on the right-hand side (10x10 nm2), and its Fourier transform, below.

The quantum materials which we will investigate encapsulate some of the great unsolved mysteries of physics. They include high-temperature superconductors, quantum-critical compounds, graphene, and topological electronic matter that can be used for error-resistant quantum computing.

![]({{ site.url }}{{ site.baseurl }}/images/respic/layers_fft.jpg){: style="width: 300px; float: left; border: 10px"} 

A main goal is to use modern technology to build the new instrumentation needed to understand these quantum materials. I learned my trade in [Seamus Davis’ SI-STM lab](http://davisgroup.lassp.cornell.edu/) and with [Felix Baumberger](http://dpmc.unige.ch/gr_baumberger/index.html), and later moved as an [ETH fellow](http://www.ethfellows.ethz.ch/) to [Andreas Wallraff’s qudev lab](http://www.qudev.ethz.ch/) where we investigated coupled cavity arrays in circuit QED. This allowed me to learn new techniques such as high frequency measurements, low temperature noise-free amplification, and quantum-limited measurements. The goal is to combine these with SI-STM.

This will enable the instrumental capabilities to visualize the different quantum mechanical degrees of freedom needed to understand next-generation quantum materials. STM will be the main method, but we use different spectroscopic-imaging techniques to visualize not only the topography, but also the density of states, spins, and other degrees of freedom hidden below the surface. -->
