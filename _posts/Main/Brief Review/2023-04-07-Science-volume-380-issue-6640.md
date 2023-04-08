---
title: "[Brief Review] Science, Volume 380 Issue 6640, 7 APR 2023"
excerpt: "Brief Review on 'Extreme ultraviolet metalens by vacuum guiding', 'Lead zirconate titanate ceramics with aligned crystallite grains', and 'Tomography of Feshbach resonance states' "


categories:
  - Brief Review
tags:
  - [Metalenses, Piezoelectrics, Collision Dynamics]

toc: true
toc_sticky: true
 
date: 2023-04-07
last_modified_at: 2023-04-07
---

This review is written by **non-expert** and used for **personal** study only.
{: .notice--danger}

# Extreme ultraviolet metalens by vacuum guiding
- **<U>Metalenses</U>**

Metasurfaces are ultra-thin, flat structures that can manipulate light at the nanoscale, offering a promising alternative to traditional bulky optical components. Until now, metasurface design has been limited to ultraviolet frequencies, but researchers have discovered a new mechanism that enables the creation of metasurfaces with a wavelength of 50 nm. This breakthrough lays the groundwork for versatile, transmissive optics technology for **extreme ultraviolet** (EUV) radiation, which has a wide range of applications.

EUV light is challenging to work with because its **high frequency** and **strong absorption** by most materials make it difficult to refract or guide. Metasurfaces with nanoholes in layers of materials that have a refractive index below 1 can serve as waveguide cores for EUV manipulation. Some suitable materials for EUV optics include aluminum, silicon, and beryllium, with ruthenium exhibiting a complex refractive index of $0.88 + 0.02i$ at $13.5 nm$.

The research team used a thin membrane of crystalline silicon containing cylindrical holes as a guiding structure that can work with any polarization to enhance the transmission of EUV light. The vacuum-guiding behavior of the holes increased the light transmission to $67\%$ and was fundamentally different from other guiding methods. The researchers developed a versatile EUV metalens by creating a library of meta-atoms based on the transmission phase of holes with diameters ranging from 20 to 80 nm in a 220-nm-thick silicon membrane. The resulting metalens achieved efficient and diffraction-limited focusing with an average transmission of 40% at 50 nm.

To experimentally validate the effectiveness of EUV metalenses, the researchers designed a focusing EUV metasurface by replicating the phase profile of an aspheric lens in a vacuum. The metalens was created for a central vacuum wavelength of $\lambda_{vac} = 50 nm$ and used silicon-on-insulator wafers. Diameter-dependent electron beam lithography doses and fabrication offsets helped achieve the desired hole diameters.

The metalens's focusing power was tested using EUV attosecond pulse trains generated via high-harmonic generation in argon gas, a method that produces ultrafast light pulses. The focal spot at the metasurface center demonstrated the EUV metalens's ability to concentrate incoming light. A knife-edge scan, a technique to determine the actual focal spot size, revealed a cylindrically symmetric Gaussian beam.

The metasurface focuses the beam to a minimum waist within 1.6 times the diffraction limit, which is the smallest possible waist size for any focusing device. The fine-granular phase control of the metasurface allows for focusing and opens up possibilities for future demonstrations of optical angular momentum plates and general holograms at EUV wavelengths.

Researchers simulated the focusing of a linearly polarized Gaussian beam, a common type of light used in optics experiments, on a metalens design with a $10 mm$ focal length and 6 mm overall optics diameter. The metalens's focus was close to the diffraction limit, with a minimum beam waist of $94 nm$, and offered better focus quality than a binary absorption zone plate, another type of focusing device.

Metasurface technology can enable the creation of transmissive optics in the EUV spectral region, leading to applications such as high-resolution microscopy and access to core-level electronic transitions. This technology can be fabricated using deep ultraviolet lithography, which is compatible with the same semiconductor foundries that produce mainstream CMOS technology, paving the way for a new generation of lithography optics. With ongoing advances in metasurface design, numerous industries are likely to benefit from the transformative potential of this technology.


>**Required Additional Study Materials**
> 
> - S. M. Kamali, E. Arbabi, A. Arbabi, A. Faraon, A review of dielectric optical metasurfaces for wavefront control. Nanophotonics7, 1041–1068 (2018).
> - Y. Intaravanne, X. Chen, Recent advances in optical metasurfaces for polarization detection and engineered polarization profiles. Nanophotonics9, 1003–1014 (2020).
> - K. Huang, J. Deng, H. S. Leong, S. L. K. Yap, R. B. Yang, J. Teng, H. Liu, Ultraviolet metasurfaces of ≈80% efficiency with antiferromagnetic resonances for optical vectorial anti-counterfeiting. Laser Photonics Rev.13, 1800289 (2019).
> - F. Krausz, M. Ivanov, Attosecond physics. Rev. Mod. Phys.81, 163–234 (2009).
> - E. D. Palik, G. Ghosh, Eds., Handbook of Optical Constants of Solids (Academic Press, 1998).
> - A. L’Huillier, K. J. Schafer, K. C. Kulander, Theoretical aspects of intense field harmonic generation. J. Phys. At. Mol. Opt. Phys.24, 3315–3341 (1991).
> - B. E. A. Saleh, M. C. Teich, Fundamentals of Photonics (Wiley, 2007).
> <details>
> <summary>Introductory material</summary>
> <div markdown="1">
> - “**Optics**” by Eugene Hecht
> - “**Introduction to Optics**” by Frank L. Pedrotti, Leno M. Pedrotti
> - “**Materials Science and Engineering: An Introduction**” by William D. Callister Jr. and David G. Rethwisch
> - “**The Science and Engineering of Materials**” by Donald R. Askeland and Pradeep P. Fulay
> </div>
> </details>

**<U>Reference</U>**

Ossiander, M. et al. Extreme ultraviolet metalens by vacuum guiding. [Science 380, 59-63 (2023).](https://www.science.org/doi/10.1126/science.adg6881)

-----

# Lead zirconate titanate ceramics with aligned crystallite grains
- **<U>Piezoelectrics</U>**

Piezoelectric materials are essential in electromechanical devices such as transducers and sensors, converting mechanical energy into electrical energy and vice versa. One widely used piezoelectric material is lead zirconate titanate (PZT) ceramics, favored for their high performance and cost-effectiveness. Researchers have sought to improve PZT ceramics by **inducing structural changes**, but this can lead to decreased thermal stability and increased complexity.

An alternative approach to enhance PZT ceramics involves engineering the ceramic grains along a specific crystal orientation, a process known as creating "textured ceramics." This method, however, has been challenging due to **unfavorable chemical reactions** between PZT powder and commonly used titanate templates.

To overcome these challenges, researchers devised two methods for fabricating textured ceramics. First, they used $Ba(Zr_{0.1}Ti_{0.9})O_{3}$ microcrystals as templates instead of the conventional $BaTiO_3$ and $SrTiO_3$. This resulted in stable templates and increased the content of the piezoelectric material in the textured PZT ceramics. Secondly, they developed a new process called "seed-passivated texturing," which involved using two different mixtures, or slurries, to create a preliminary material called "green tape." This green tape achieved the desired composition after being heated or sintered, leading to textured PZT ceramics with high-quality texture and a high percentage of piezoelectric material.

The researchers then examined the uniformity of the composition of the textured ceramic using various microscopy and spectroscopy techniques, including scanning electron microscopy (SEM), electron probe microanalysis (EPMA), and scanning transmission electron microscopy (STEM) with energy-dispersive X-ray spectroscopy (EDS) and electron energy loss spectroscopy (EELS). These tests revealed a consistent distribution of the main elements with minimal separation, indicating that the composition of the material was uniform and acceptable.

By using computer simulations called phase-field simulations, the researchers analyzed the effect of composition fluctuations on the material's electrical and piezoelectric properties. They found that these fluctuations had minimal impact ($<5\%$) due to the acceptable uniformity of the textured ceramics. They also confirmed the high quality of the material's texture using x-ray diffraction (XRD) and electron backscatter diffraction (EBSD) techniques, which showed that most of the grains were oriented in the same direction, specifically along the $<001>$ direction.

The researchers then studied the piezoelectric properties of the textured PZT ceramics, finding that certain orientations, such as the $<001>$-textured rhombohedral PZT ceramics, led to improved piezoelectric performance, including enhanced values of $d_{33}$ (a measure of piezoelectric charge constant) and $k_{33}$ (an electromechanical coupling factor). They also found that these textured ceramics had superior piezoelectric voltage coefficients ($g_{33}$) compared to most other ferroelectric materials, making them ideal for energy harvesting applications.

The researchers also investigated the material's response to electric fields, noting that the induced strain was larger in textured PZT ceramics than in other materials. This was mainly due to the polarization rotation within the material. They also observed that the thermal stability of the textured ceramic was good, maintaining its structure up to $300°C$, and that its piezoelectric properties improved with temperature, making it advantageous for use in piezoelectric actuators.

In conclusion, the researchers developed a new seed-passivated texturing method for creating high-quality textured PZT ceramics, which shows promise for improving the performance of next-generation piezoelectric devices. This new method overcomes previous challenges in fabricating textured ceramics and offers a new route to produce advanced materials for a wide range of applications, enabling further research into novel piezeoelectric materials.


>**Required Additional Study Materials**
>
> - B. Jaffe, W. R. Cook, H. Jaffe, Piezoelectric Ceramics (Academic Press, 1971).
> - M. G. Kang, W. S. Jung, C. Y. Kang, S. J. Yoon, Recent Progress on PZT Based Piezoelectric Energy Harvesting Technologies. Actuators 5, 5 (2016).
> - M. Kimura, A. Ando, D. Maurya, S. Priya, Advanced Piezoelectric Materials (Elsevier, 2010).
> - H. Thomann, Piezoelectric ceramics. Adv. Mater. 2, 458–463 (1990).
> - S. Zhang, F. Li, High performance ferroelectric relaxor-PbTiO3 single crystals: Status and perspective. J. Appl. Phys. 111, 031301 (2012).
> <details>
> <summary>Introductory material</summary>
> <div markdown="1">
> - “**Materials Science and Engineering: An Introduction**” by William D. Callister Jr. and David G. Rethwisch
> - “**The Science and Engineering of Materials**” by Donald R. Askeland and Pradeep P. Fulay.
> - “**Chemistry: The Central Science**” by Theodore L. Brown, H. Eugene LeMay Jr., Bruce E. Bursten, Catherine J. Murphy, Patrick M. Woodward, and Matthew W. Stoltzfus
> - “**Chemical Principles: The Quest for Insight**” by Peter Atkins and Loretta Jones
> </div>
> </details>

**<U>Reference</U>**

Li, J. et al. Lead zirconate titanate ceramics with aligned crystallite grains. [Science 380, 87-93 (2023).](https://www.science.org/doi/10.1126/science.adf6161)

-----

# Tomography of Feshbach resonance states
- **<U>Collision Dynamics</U>**

Feshbach scattering resonances are critical phenomena in energy transfer during atomic and molecular collisions. These resonances can be observed in various collision situations by adjusting energy levels or the strength of magnetic fields. Researchers have developed a method to separate vibrational Feshbach resonances and study collision pathways, allowing them to detect quantum signatures even in systems with strong interactions and anisotropy, or directional dependence.

In simpler terms, the method involves the interaction of a ground-state molecule with a metastable noble gas atom, which leads to the **Penning ionization** process. The Feshbach resonance states that emerge from this process are described by a mathematical representation called the free molecule basis, without changing the molecule's rotational quantum number. The final distribution of quantum states is seen in the molecular ion's velocity distribution, which is analyzed using a method called electron-ion coincidence measurements.

> **Penning ionization**
>
>Penning ionization is a process that occurs when an atom or molecule in a metastable state (an excited state with a relatively long lifetime) interacts with another atom or molecule in its ground state (lowest possible energy state). In this process, the energy from the metastable atom or molecule is transferred to the ground-state atom or molecule, causing the latter to lose an electron and become ionized. The metastable atom or molecule, in turn, transitions to a lower-energy state.
>
><p align="center">
  <img src="https://user-images.githubusercontent.com/79438062/230532023-f910bb4a-e4a0-43c7-807a-fa9d86bcc08b.png" alt="Source: Wikipedia">
<br> <b>The process of ionization interaction between excited molecule and target molecule. </b> Source: Wikipedia </p>
>
>**Penning ionization process**:
>1.	A metastable atom or molecule (designated as A*) with excess energy approaches a ground-state atom or molecule (designated as B) that is capable of being ionized.
>2.	As A* gets close to B, the excess energy from A* is transferred to one of B's electrons.
>3.	This energy transfer causes the electron in B to gain enough energy to overcome the attractive force holding it to the nucleus of B, resulting in the ionization of B.
>4.	The ionized atom or molecule (B+) and the released electron (e-) move away from each other due to their mutual electrostatic repulsion.
>5.	The metastable atom or molecule A* transitions to a lower-energy state (A) as it has transferred its excess energy to B.

The unique characteristics of each Feshbach resonance state in the final-state distribution depend on three factors: the energy of the Feshbach state, the total angular momentum, and the vibrational quantum number (a property related to the molecule's vibrations).

The researchers examined energy distributions in collisions between metastable Ne* or He* atoms and H2 molecules, using a special device called a coincidence double velocity map imaging apparatus. Coincidence detection is a technique that helps identify the mass of particles, determine the initial state of the system, and correct imaging images for electron recoil (an effect that occurs during the ionization process).

During the experiments, they acquired images called ion and electron VMI images for $Ne*-H_2$ collisions. The ion VMI image was divided into different sections, each representing a stage of data analysis. A technique called tomography was used to determine the energy distribution of molecular ions and observe how Feshbach resonances relate to another mathematical representation called the continuum-basis set. The resonance energy values were determined for both $Ne-H_2^+$ and $He-H_2^+$ systems.

To verify the nature of resonances in the two systems, they performed quantum wave packet calculations. They also carried out full coupled-channel calculations with converged bases for both systems, finding numerical results that matched experimental data quite well. They developed a statistical model to describe the final-state distribution, but found deviations from the model in some cases. However, the overall agreement between experiment and theory indicates high accuracy.

Feshbach resonance states have unique quantum signatures in the final-state distribution. This knowledge can be used to control the final-state distribution by manipulating the quantum state of the Feshbach state itself. This can be achieved by taking advantage of different shape resonances (a type of resonance that depends on the geometry of the system) in the neutral collision complex and performing experiments under specific conditions, called the p-wave limit.


>**Required Additional Study Materials**
>
> - C. Chin, R. Grimm, P. Julienne, E. Tiesinga, Feshbach resonances in ultracold gases. Rev. Mod. Phys. 82, 1225–1286 (2010).
> - A. Rohrbacher, N. Halberstadt, K. C. Janda, The Dynamics of Noble Gas—Halogen Molecules and Clusters. Annu. Rev. Phys. Chem. 51, 405–433 (2000).
> - P. Siska, Molecular-beam studies of Penning ionization. Rev. Mod. Phys. 65, 337–412 (1993).
> <details>
> <summary>Introductory material</summary>
> <div markdown="1">
> - “**Atomic Physics**” by Christopher J. Foot
> - “**Introduction to Atomic Physics**” by Max Born
> - “**Principles of Quantum Mechanics**” by R. Shankar
> - “**Quantum Mechanics: Concepts and Applications**” by Nouredine Zettili
> </div>
> </details>

**<U>Reference</U>**

Margulis, B. et al. Tomography of Feshbach resonance states. [Science 380, 77-81 (2023).](https://www.science.org/doi/10.1126/science.adf9888)