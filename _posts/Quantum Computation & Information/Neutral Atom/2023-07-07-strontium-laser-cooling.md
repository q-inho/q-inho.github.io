---
title: "Strontium Isotopes: Laser Cooling and Trapping Atom"
excerpt: "Exploration into the unique properties of strontium isotopes, focusing on their pivotal role in advancing laser cooling techniques."

header:
  overlay_image: 
  overlay_filter: 

categories:
  - Neutral Atom
tags:
  - [Quantum Computing, Strontium]

toc: true
toc_sticky: true
 
date: 2023-07-07
last_modified_at: 2023-07-07
---

# Atomic Strontium and Its Isotopes

Strontium, a fascinating element in the periodic table, is characterized by its unique isotopic composition. It comprises four isotopes, each with distinct properties that contribute to intriguing physical models. Among these isotopes, three are bosonic, while one is fermionic, namely $^{87}Sr$.

The fermionic isotope, $^{87}Sr$, presents a challenge for laser cooling due to its unique properties. However, it is this very complexity that makes it a valuable asset in the development of intriguing physical models. On the other hand, the bosonic isotopes of strontium simplify experimental considerations, thereby facilitating research and exploration.

The performance of evaporative cooling techniques is largely determined by the scattering lengths of the isotopes. Interestingly, the most abundant isotope, $^{88}Sr$, is unsuitable for these techniques, adding another layer of complexity to the study of strontium.

Strontium's level structure is characterized by singlet-triplet manifolds, a consequence of its $S=1$ electronic structure. This unique feature enhances the strontium toolbox, enabling researchers to explore new frontiers in the field.

The fermionic isotope, $^{87}Sr$, exhibits fine and hyperfine structure mixing, which allows for ultra-narrow optical transitions. These transitions, which are forbidden in the strict quantum number picture, make $^{87}Sr$ a valuable tool for laser cooling and trapping.

<p align="center">
  <img width="610" src="https://github.com/q-inho/q-inho.github.io/assets/79438062/b19246e8-a9e1-4b7d-9a35-eeaa3914d9f9">
<br> <b>Figure 1. Level diagram of atomic strontium including all relevant optical transitions for laser cooling and trapping </b>. Source: (Baumgartner)$^{[1]}$
</p>

Strontium's broad $^1S_0$ → $^1P_1$ transition at 461 nm enhances radiation pressure and simplifies cooling. Furthermore, its multiple higher-lying states in the triplet manifold allow for interesting trap scenarios in dipole traps. The isotope shifts on the blue transition are small, enabling an experiment to address all isotopes with a single laser system.

# Magneto-Optical Traps (MOTs)

Strontium can be trapped in a large Magneto-Optical Trap (MOT) using a broad and narrow transition. This technique allows for extremely low temperatures to be achieved in another MOT on the narrow intercombination line, bringing strontium close to degeneracy.

The blue MOT for strontium uses transitions from the $^3P_J$ manifold to the $6s$ $^3S_1$ states. This process allows atoms to be pumped back to $^3P_1$ and then decay back to the ground state $^1S_0$. The required wavelengths for these transitions are 679 nm and 707 nm.

The fermionic isotope has a small hyperfine splitting and broad linewidth, which makes the performance of the fermionic MOT inferior to that of the bosonic MOT. The Red MOT can be used as a second cooling stage to further cool the already cooled atom cloud of the blue MOT. However, there is a significant mismatch in the ideal magnetic field gradients and the achieved bandwidths in velocity space of the two MOTs.

Dipole traps with certain wavelengths cause identical light shifts for both the $^3P_J$ states and the ground state $^1S_0$, known as **magic wavelengths**. These have been used in optical lattice clocks and are required for proposed sideband cooling strategies. A magic wavelength between $^1S_0$ and $^3P_1$ that is attractive is required for the proposed sideband cooling strategy within the tweezers.

A magic crossing for the $^1S_0 \rightarrow ^1P_1$ transition was found using a formula. 

$$

\frac{\tilde{A}_{ik}}{\tau _L} = \frac{(2J_i + 1) \begin{Bmatrix}
J_i & J_k & 1 \\
L_K & L_i & S
\end{Bmatrix}^2}{\sum^{|L_i + S|}_{J=|L_i-S|}(2J + 1) \begin{Bmatrix}
J & J_k & 1 \\
L_K & L_i & S
\end{Bmatrix}^2} = \sum^{J_k}_{m_k = - J_k} (2J_k + 1) \begin{pmatrix}
J_i & 1 & J_k \\
m_i & p & -m_k
\end{pmatrix}^2

$$

Here, $J'$s are the total angular momenta, $L$ the electron angular momenta levels (manifolds), $m$ are the magnetic sublevels, and $p$ are light polarization as a spinor. This is cross-checked by reproducing the magic crossing of the $^1S_0 \rightarrow ^3P_0$ transition. The results showed a magic crossing at $\lambda m = (515 \pm 3)$ nm for the $^1S_0$ and $^3P_1$ state, with polarizability depending on the polarization and magnetic levels of the $^3P_1$ state. High-NA objectives used for optical tweezers can introduce spatially-dependent polarizations, causing non-magic conditions at certain points within the trap.


**<U>Reference</U>**

1. Baumgartner, A. A new apparatus for trapping and manipulating single Strontium atoms. (2017). 