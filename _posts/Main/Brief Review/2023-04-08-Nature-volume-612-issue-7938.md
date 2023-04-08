---
title: "[Brief Review] Nature, Volume 612 Issue 7938, 1 December 2022"
excerpt: "Brief Review on 'Traversable wormhole dynamics on a quantum processor', 'A photonic integrated continuous-travelling-wave parametric amplifier', 'An integrated imaging sensor for aberration-corrected 3D photography', and 'Discovery of chalcogenides structures and composition using mixed fluxes' "


categories:
  - Brief Review
tags:
  - [Materials Chemistry, Quantum Physics,Integrated Optics, Imaging Techniques]

toc: true
toc_sticky: true
 
date: 2023-04-09
last_modified_at: 2023-04-09
---

This review is written by **non-expert** and used for **personal** study only.
{: .notice--danger}

# Discovery of chalcogenides structures and compositions using mixed fluxes
- **<U>Materials Chemistry</U>**

Predicting the outcomes of creating new extended solid materials is quite challenging, making exploratory synthesis an essential tool for discovering novel materials. Scientists have developed a versatile synthesis approach that helps control reaction pathways and phase selection, ultimately leading to the creation of 30 new compounds with unique structural types.

Solubility, which plays a crucial role in synthesis, can be regulated by using a mixed flux—a combination of an effective solvent and an anti-solvent. Scientists selected $AOH$ and $AX$ as adjustable components in the flux for creating chalcogenide systems. To further fine-tune solubility, they incorporated mixed alkali ions into the hydroxide. This method successfully resulted in $30$ previously unreported compounds.

> **Chalcogenide systems**
>
>Chalcogenide systems are a class of materials that consist of one or more chalcogen elements (oxygen, sulfur, selenium, and tellurium) combined with other elements. These materials exhibit a wide range of properties, making them suitable for various applications in different fields.
>
>Chalcogenides can be found in different forms, such as glasses, crystals, and thin films. They have unique electrical, optical, and thermal properties, which result from the specific bonding characteristics of chalcogen elements. The chalcogen atoms form covalent bonds with other elements (such as metals or semiconductors), creating a diverse set of materials with tunable properties.

By reducing the concentration of hydroxide ions ($OH$), they observed a mixture of two types of products, with copper ($Cu$) atoms occupying irregular positions in a 2D honeycomb lattice. As they increased solubility and the concentration of another component ($A_2Q$), the complexity of the structures decreased. For a specific case ($Q=S$), they were able to produce a double-chained sulfide structure by adjusting the $OH$ concentration at different temperatures.

Introducing barium ($Ba$) during the reaction led to the observation of new compounds involving $Ba$, $Cu$, and other elements. These $Ba$-containing compounds are favored at high reactant solubility and temperature due to the lower solubility of the more complex products. Lithium ($Li$) substitution in one compound is driven by a more favorable mixing behavior and a lower synthesis temperature. Adjusting the sodium ($Na$) to $Li$ ratio in a specific mixture allows control over the reaction outcome and the formation of a unique mixed-anion compound.

By using the $AOH/AX$ fluxes, scientists synthesized mixed-anion compounds with tunnel-type structures. They also observed some intermediate structures, which served as precursors to more complex 2D structures. The solubility of certain building blocks increases with specific ratios. Introducing barium ions led to the **creation of distinctive structures**.

To better understand the relationship between stability and synthetic conditions, scientists performed a comprehensive analysis using in situ powder X-ray diffraction (PXRD), which helps **detect unknown intermediates** and **previously unreported phases**. Including barium oxide ($BaO$) in the mix changes the solubility, enabling the creation of a diverse array of structures. They also used thermodynamic concepts to analyze the dissolution and recrystallization processes of certain compounds.

They used density functional theory calculations to study the stability of products in the synthesis of complex chains of atoms. Stability decreased with more straightforward structures and a higher $Na/Cu$ ratio, suggesting a higher likelihood of instability. By manipulating variables like temperature and the ratio of $AOH/AX$, they could control the complexity and dimensionality of the resulting structures. This synthesis approach can **improve the efficiency of exploratory syntheses** and guide the discovery of a wide range of materials.


>**Required Additional Study Materials**
>
> - Schmidt, J., Marques, M. R. G., Botti, S. & Marques, M. A. L. Recent advances and applications of machine learning in solid-state materials science. NPJ Comput. Mater. 5, 83 (2019).
> - Oganov, A. R., Pickard, C. J., Zhu, Q. & Needs, R. J. Structure prediction drives materials discovery. Nat. Rev. Mater. 4, 331–348 (2019).
> - Pöhls, J.-H., Heyberger, M. & Mar, A. Comparison of computational and experimental inorganic crystal structures. J. Solid State Chem. 290, 121557 (2020).
> <details>
> <summary>Introductory material</summary>
> <div markdown="1">
> - “**Chalcogenide: From 3D to 2D and Beyond**” by Xinyu Liu, Sanghoon Lee, Jacek Furdyna, Tengfei Luo, and Yong-Hang Zhang
> - “**Amorphous Chalcogenide Semiconductors and Related Materials**” by Keiji Tanaka, and Koichi Shimakawa
> </div>
> </details>

**<U>Reference</U>**

Zhou, X., Kolluru, V.S.C., Xu, W. et al. Discovery of chalcogenides structures and compositions using mixed fluxes. [Nature 612, 72–77 (2022). ](https://doi.org/10.1038/s41586-022-05307-7)

-----

# Traversable wormhole dynamics on a quantum processor
- **<U>Quantum Physics</U>**

Traversable wormholes present a opportunity to examine the connection between entanglement and geometry using a concept called holographic duality, which links quantum theories to gravitational theories. By manipulating the connections between the outer regions of two black holes, wormholes can be made traversable, enabling the passage of information through them.

The Google Sycamore processor has been utilized to showcase traversable wormhole dynamics using **nine** qubits, a type of quantum bit. This demonstration is related to a specific kind of wormhole called an anti-de Sitter-Schwarzschild wormhole. As the qubit travels through the wormhole, the information is scrambled in one subsystem before being unscrambled and refocused in another subsystem.

In a quantum system, there's a state called the TFD state that corresponds to a specific type of wormhole, where two entangled quantum systems exist at a particular temperature. Wormhole teleportation maintains the sequence of transmitted quantum information as it passes through the wormhole, unlike other teleportation methods that involve random unitary dynamics.

The study investigates the behavior of traversable wormholes using a simulation that models a quantum system with a certain number of particles called fermions. This simulation is called a many-body simulation of an SYK (Sachdev-Ye-Kitaev) system. Researchers used a specific model with q couplings to demonstrate the effects of gravity in small systems. The quantum teleportation process involves setting up the system in a particular way, initializing the TFD state, and then applying an interaction (eiμV) with a negative μ across both subsystems, which creates a sort of "shockwave" to help the qubit travel through the wormhole. A measurement called mutual information (IPT) is used to confirm that quantum teleportation has occurred within a specific time window.

This mutual information reaches its peak value when certain conditions are met, specifically when μ is negative, and the number of fermions (N) is large. Researchers can observe this behavior by adjusting the timing of when information is sent into and read out from the system. Even when simplifying the quantum system through a process called sparsification, the essential features of gravity are preserved, making it possible to create a small circuit for wormhole teleportation.

By using techniques similar to training a neural network, researchers optimized certain aspects of the quantum system through backpropagation across a wormhole teleportation protocol. This optimization process resulted in a simpler, sparse Hamiltonian model that still accurately describes the behavior of the original system and requires only seven of the original fermions.

The simplified model was tested through two approaches to ensure it still accurately represented gravitational physics. It was found to replicate the relevant dynamics of the dense SYK Hamiltonian and satisfy general holographic system criteria. The learned Hamiltonian exhibits scrambling and thermalization similar to the original SYK model, suggesting that the boundary lies near the horizon.

Perfect size winding, a particular property of the system, is essential for traversable wormhole behavior in quantum systems with a nearly AdS 2 bulk. The simplified model was found to possess this property, which is responsible for enabling teleportation and is not caused by generic chaotic dynamics or direct swapping.

The simplified model was used in a quantum experiment on the Google Sycamore superconducting qubit array, where it was able to closely reproduce the expected behavior. The experiment showed that **teleportation was more efficient** when a specific type of shockwave, a negative energy one, was used. This asymmetric signature aligns with the physical interpretation that the qubit undergoes teleportation through the wormhole.

The protocol can be scaled up to larger systems, and machine learning techniques were employed to create a small-N sparse Hamiltonian that retains the crucial aspects of gravitational physics. This means that classical simulations are not required for systems with a certain number of fermions ($N = O(50)$). This work successfully demonstrated traversable wormhole dynamics in a lab setting, indicating that future quantum computers may help us gain new insights into gravity.

To further advance our understanding of quantum gravity, future research should focus on measuring certain inelastic effects within larger systems ($N = O(100) $ fermions). This would involve testing methods for amplifying weak signals and implementing techniques to minimize errors. Validating these results on different platforms is essential for ensuring the accuracy of the findings.

Quantum experiments on chips could lead to exciting discoveries about the relationship between quantum mechanics and gravity. Moreover, the protocol can be made more efficient and scalable by incorporating machine learning techniques, which could lead to the construction of small-N sparse Hamiltonians that maintain the critical aspects of gravitational physics. In turn, this would eliminate the need for classical simulations in systems with a specific number of fermions.

As quantum computing technology continues to evolve, further experimentation and refinement of these protocols will likely reveal even more about the fascinating and complex relationship between quantum mechanics, entanglement, and the nature of gravity.



>**Required Additional Study Materials**
>
> - Visser, M. Lorentzian Wormholes: From Einstein to Hawking. Computational and Mathematical Physics (American Institute of Physics, 1995).
> <details>
> <summary>Introductory material</summary>
> <div markdown="1">
> - “**Modern Quantum Mechanics**” by J. J. Sakurai and Jim Napolitano
> - “**A First Course in General Relativity**” by Bernard Schutz
> </div>
> </details>

**<U>Reference</U>**

Jafferis, D., Zlokapa, A., Lykken, J.D. et al. Traversable wormhole dynamics on a quantum processor. [Nature 612, 51–55 (2022). ](https://doi.org/10.1038/s41586-022-05424-3)

-----

# A photonic integrated continuous-travelling-wave parametric amplifier
- **<U>Integrated Optics</U>**

Optical signal amplification is a key aspect of science and technology. **Erbium-doped fiber amplifiers** (EDFAs) have significantly improved optical communications by allowing signals to travel long distances and increasing communication bandwidth affordably. In simpler terms, EDFAs have enabled more efficient information transmission over vast distances through fiber-optic cables.

Apart from EDFAs, there are parametric amplifiers, such as **travelling-wave parametric amplifiers** (TWPAs), developed for use in microwave technology. TWPAs are particularly useful in quantum information processing because they are quantum-limited, provide a wide range of gain, and enable precise measurements of quantum systems, like **superconducting qubits**.

Parametric amplifiers have unique properties that allow them to **amplify signals** in wavelength ranges not accessible by conventional gain media. Operating close to the fundamental quantum noise limit, they produce minimal noise during amplification, resulting in clearer and more accurate signal transmission. Recently, researchers have explored new materials and techniques to create more efficient parametric amplifiers. However, challenges remain, including limitations in material properties and fabrication processes.

To address these challenges, researchers have developed a new type of parametric amplifier based on a photonic integrated circuit that operates in a continuous-wave regime. This amplifier can provide gain even when there is a loss of connection between the fiber and the chip. The innovation uses a material called $Si_3N_4$, featuring unique properties that enable low-loss, tightly confined light and high power handling capabilities.

Researchers used the **photonic Damascene reflow process** to fabricate ultralow-loss, dispersion-engineered, nonlinear $Si_3N_4$ integrated waveguides. These crack-free $Si_3N_4$ photonic integrated circuits exhibit tight optical confinement, high peak and average power-handling capabilities, low Brillouin gain, ultralow optical losses, and negligible nonlinear absorption in telecommunication bands, all of which contribute to the feasibility of continuous-net-gain TWPAs.

In single-pump parametric amplification, a process called nonlinear degenerate four-wave mixing transfers power from a strong pump to a signal within an optical waveguide. This process enables the efficient transfer of energy from one light source to another. Waveguide-based TWOPA ( a photonic-integrated-circuit-based continuous-wave TWPA in the optical domain) systems can potentially provide a much broader range of amplification compared to EDFAs, with bandwidths exceeding 10 terahertz (THz).

The $Si_3N_4$ photonic chip was tested for its ability to transmit light, its dispersion profile (how different wavelengths of light spread out), and how much light was lost during propagation. The chip performed well, transmitting up to $12\%$ of the light through a 2-meter-long spiral, with an average transmission of $10\%$ in a specific wavelength range.

The experimental setup successfully measured the parametric gain and frequency-conversion efficiency of the system, achieving up to $2$ decibels (dB) of net gain on the photonic chip. The system maintained its performance without the need for any special techniques to counteract stimulated Brillouin scattering, which can degrade signal quality.

Despite its anomalous group velocity dispersion (GVD), the $Si_3N_4$ waveguide's gain and frequency conversion bandwidths measured $20 nm$. The results align with numerical calculations using the full set of nonlinear equations in the frequency domain.

In conclusion, researchers have developed a photonic-integrated-circuit-based continuous-net-gain travelling-wave parametric amplifier using a 2-meter-long $Si_3N_4$ integrated waveguide on a compact silicon chip. This innovation can be combined with various existing integrated photonic devices and applications. Advanced dispersion-engineering techniques and highly nonlinear photonic integrated materials have the potential to enable even more compact and higher gain TWPAs for future generations of optical communication systems and quantum information processing.


>**Required Additional Study Materials**
>
> - Devoret, M. H. & Schoelkopf, R. J. Superconducting circuits for quantum information: an outlook. Science 339, 1169–1174 (2013).
> - Marhic, M. E. et al. Fiber optical parametric amplifiers in optical communication systems. Laser Photonics Rev. 9, 50–74 (2015).
> - Moss, D. J., Morandotti, R., Gaeta, A. L. & Lipson, M. New CMOS-compatible platforms based on silicon nitride and Hydex for nonlinear optics. Nat. Photon. 7, 597–607 (2013).
> - Kippenberg, T. J., Gaeta, A. L., Lipson, M. & Gorodetsky, M. L. Dissipative Kerr solitons in optical microresonators. Science 361, eaan8083 (2018).
> <details>
> <summary>Introductory material</summary>
> <div markdown="1">
> - “**Principles of Photonic Integrated Circuits: Materials, Device Physics, Guided Wave Design**” by Richard Osgood jr. and Xiang Meng
> </div>
> </details>

**<U>Reference</U>**

Riemensberger, J., Kuznetsov, N., Liu, J. et al. A photonic integrated continuous-travelling-wave parametric amplifier. [Nature 612, 56–61 (2022). ](https://doi.org/10.1038/s41586-022-05329-1)

-----

# An integrated imaging sensor for aberration-correction 3D photography
- **<U>Imaging Techniques</U>**

Two-dimensional (2D) imaging sensors, commonly found in everyday cameras, face difficulties in creating detailed 3D images due to optical aberrations and limitations of light field freedoms. These issues make it challenging to obtain high-quality depth maps, which represent 3D structures. Traditionally, specially designed lenses have been used to correct these aberrations, but as the complexity of imaging systems increases, this method becomes less effective.

Some alternative solutions, such as metalenses, free-form optics, and image deblurring algorithms, have been explored to address these issues. However, they come with their own set of limitations and require specific conditions and precise calculations.

Adaptive optics is another method used to correct aberrations, which involves adjusting mirrors or using spatial light modulators to control the light path. Unfortunately, this approach has a narrow field of view and is expensive. A newly proposed meta-imaging sensor overcomes these challenges by using digital adaptive optics, allowing it to capture 3D images with a large space-bandwidth product (a measure of the imaging system's performance) at a lower cost.

The meta-imaging sensor can produce high-quality, all-in-focus images up to gigapixel resolution using just one lens. It also offers significant improvements in resolution when faced with nonuniform aberrations, supports multisite aberration corrections on large telescopes, and generates high-quality depth maps quickly and accurately. These capabilities make it suitable for a variety of industrial applications.

This innovative sensor combines a coded **microlens array** with a **conventional imaging sensor** to capture 4D spatial-angular information, which helps create images with high-frequency details. The sensor utilizes a circular aperture to minimize artifacts and employs high-speed periodic drifting of the microlens array to enhance the spatial sampling density, which increases the captured detail. The meta-imaging sensor can replace conventional sensors **without** needing additional hardware changes.

A key advantage of the meta-imaging sensor over traditional 2D sensors is its ability to **generate complex**, **high-quality** images in post-processing without requiring extra optical devices. It is also more resistant to aberrations and can refocus blurry images during post-processing using a **digital adaptive optics** (DAO) framework. This sensor can correct multiple sites of aberrations without slowing down data acquisition and can apply different corrections across a wide **field of view** (FOV).

As camera lenses become more advanced, their cost and size increase, making them challenging to use in lightweight or portable devices. The meta-imaging sensor provides a scalable solution to these problems, achieving effective $48$-megapixel imaging with consistent performance across the entire FOV, outperforming conventional 2D sensors. This development paves the way for high-resolution imaging in portable devices with compact, low-cost optical systems.

In contrast to conventional 2D sensors, which have **limited depth** of field and are affected by environmental aberrations, the meta-imaging sensor is **more robust** and offers an extended depth of field. Experiments show that the meta-imaging sensor maintains resolution and consistent performance even with environmental aberrations, while 2D sensors experience severe degradation.

An optical-flow-based algorithm is used to **correct nonuniform motion artifacts** in the meta-imaging sensor, preserving spatial resolution for static scenes and enabling **instantaneous synthetic aperture** (ISA) without motion artifacts or speed reduction. This is achieved by synthesizing high-resolution images using a sliding window without decreasing the rate at which images are captured.

For large-scale optical astronomical surveys, atmospheric turbulence affects the spatial resolution of ground-based telescopes. Hardware adaptive optics techniques can help, but they are expensive and have a small effective FOV. The meta-imaging sensor provides a cost-effective solution for large telescopes, achieving better resolution and contrast than conventional 2D sensors. Its robustness to aberrations and consistent long-term performance make it a promising tool for astronomical research.

Meta-imaging sensors offer an affordable solution for applications like autonomous driving and industrial inspections, as they deliver higher precision in both lateral and axial domains compared to traditional light-field cameras. The meta-imaging sensor produces higher resolution and a more **accurate depth map** than traditional light-field cameras, even capturing minute structures that are difficult to distinguish.

Two essential features for the **instantaneous synthetic aperture** (ISA) with **digital adaptive optics** (DAO) in the meta-imaging sensor are the wave-optics model for high-resolution reconstruction with aberration correction and the integrated scanning process of the microlens array. Learning-based methods, like those used in artificial intelligence, can be employed with pre-trained models to further enhance the meta-imaging sensor's output using data priors. Additionally, more advanced algorithms with parallel computing devices can be designed to improve performance or reduce computational costs.

The proposed meta-imaging sensor opens up new possibilities for computational imaging in a wide range of applications, achieving levels of image quality and detail that were previously unattainable with traditional 2D sensors. Its innovative design and capabilities make it a promising tool for various industries and research fields, especially for those requiring high-resolution imaging in portable devices or under challenging environmental conditions.



>**Required Additional Study Materials**
>
> - Lichtman, J. W. & Conchello, J.-A. Fluorescence microscopy. Nat. Methods. 2, 910–919 (2005).
> - Yun, S. H. & Kwok, S. J. J. Light in diagnosis, therapy and surgery. Nat. Biomed. Eng. 1, 0008 (2017).
> - Hardy, J. W. Adaptive Optics for Astronomical Telescopes (Oxford Univ. Press, 1998).
> - Sasián, J. Introduction to Aberrations in Optical Imaging Systems (Cambridge Univ. Press, 2013).
> - Roggemann, M. C. & Welsh, B. M. Imaging through Turbulence (CRC, 2018).
> - Conrady, A. E. Applied Optics and Optical Design, Part One (Courier, 2013).
> - Wu, R. et al. Design of freeform illumination optics. Laser Photonics Rev. 12, 7 (2018).
> - Booth, M. J. Adaptive optics in microscopy. Philos. Trans. R. Soc., A 365, 2829–2843 (2007).
> - Booth, M. J. Adaptive optical microscopy: the ongoing quest for a perfect image. Light: Sci. Appl. 3, e165 (2014).
> - Robertson, B. E. et al. Galaxy formation and evolution science in the era of the Large Synoptic Survey Telescope. Nat. Rev. Phys. 1, 450–462 (2019).

**<U>Reference</U>**

Wu, J., Guo, Y., Deng, C. et al. An integrated imaging sensor for aberration-corrected 3D photography. [Nature 612, 62–71 (2022). ](https://doi.org/10.1038/s41586-022-05306-8)