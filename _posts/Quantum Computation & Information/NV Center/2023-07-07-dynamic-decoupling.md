---
title: "NV Center: Interactions of Electron-Nuclear Gates"
excerpt: "Interactions, specifically focusing on the role of dynamical decoupling (DD) sequences and the impact of external magnetic fields on the operation of electron-nuclear gates."

header:
  overlay_image: 
  overlay_filter: 

categories:
  - NV Center
tags:
  - [Quantum Computing]

toc: true
toc_sticky: true
 
date: 2023-07-07
last_modified_at: 2023-07-07
---

In the realm of quantum mechanics, electron spins and nuclear spins interact through a process known as hyperfine interaction. Early multi-qubit experiments in diamond leveraged this interaction, using the electron spin in conjunction with the nitrogen nuclear spin. These experiments also involved one or two strongly coupled $^{13}C$ spins.

In this setup, hyperfine-split transitions can be discerned in the electron spin resonance (ESR) spectrum. This allows for the execution of conditional logic by applying weak microwave pulses that selectively drive individual transitions. However, the probability of observing several strongly-coupled $^{13}C$ spins for a single Nitrogen-Vacancy (NV) center is quite low.

A significant advancement was made in 2012 when three independent experiments demonstrated that tailored dynamical decoupling (DD) sequences could be used to detect and control individual nuclear spins $^{[2-4]}$. This breakthrough provided access to many more spins surrounding a single NV center.

The Hamiltonian terms for the electron spin and a single $^{13}C$ are given by the equation 

$$
H = \omega _L I_z + A_\parallel S_z I_z + A_\perp S_z I_x
$$

In this equation, we assume a well-aligned magnetic field and consider the interaction picture for the electron energy splitting. The far-detuned $m_s = +1$ level is neglected for simplicity, and the indices $i$ and $C$ from the hyperfine components and $^{13}C$-spin operators are dropped.

The nuclear spin experiences different evolution depending on the state of the electron spin. In the $m_s = 0$ state, the nuclear spin undergoes simple Larmor precession around the axis defined by the external magnetic field. However, in the $m_s = -1$ state, the nuclear spin rotates around a tilted axis at a modified frequency.

To realize non-trivial rotations, we consider a dynamical decoupling sequence of primitive form: $(\tau – \pi – 2 \tau – \pi – \tau)$. The corresponding nuclear spin unitary evolution is given by 

$$
\begin{aligned}
V_0 &= exp[−iH_0\tau]\cdot exp[−2iH_1\tau]\cdot exp[−iH_0 \tau] = exp[−i \theta (\textbf{I} \cdot \mathbf{n _0})], \\ 
V_1 &= exp[−iH_1\tau]\cdot exp[−2iH_0\tau]\cdot exp[−iH_1 \tau] = exp[−i \theta (\textbf{I} \cdot \mathbf{n _1})]
\end{aligned}
$$

The choice of external magnetic field plays a significant role in the DD gate dynamics. In the high-field regime, the number of decoupling pulses required to realize the $\pi/2$ rotation scales linearly with the magnetic field. At very high magnetic fields, sub-nanosecond temporal resolution is required to accurately address the resonances.

For an unstudied NV center to be used for multi-qubit experiments, the first step is to perform preliminary characterization of the nuclear spin environment. This process, known as dynamical decoupling spectroscopy, provides information about individual $^{13}C$ spins and the suitable $\tau$ values for their DD-based control.


**<U>Reference</U>**

1. Bradley, C. E. Order from Disorder: Control of Multi-Qubit Spin Registers in Diamond. (2021).
2. Taminiau, T. H. et al. Detection and control of individual nuclear spins using a weakly coupled electron spin. Physical Review Letters 109, (2012). 
3. Zhao, N. et al. Sensing single remote nuclear spins. Nature Nanotechnology 7, 657–662 (2012).
4. Kolkowitz, S., Unterreithmeier, Q. P., Bennett, S. D. &amp; Lukin, M. D. Sensing distant nuclear spins with a single electron spin. Physical Review Letters 109, (2012).  