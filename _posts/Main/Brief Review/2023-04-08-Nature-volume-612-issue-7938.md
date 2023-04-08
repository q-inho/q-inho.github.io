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