---
title: "NV Centre Spin Relaxation and Quantum Interactions at Low Temperatures"
excerpt: "."

header:
  overlay_image: 
  overlay_filter: 

categories:
  - NV Center
tags:
  - [Quantum Computing]

toc: true
toc_sticky: true
 
date: 2023-07-06
last_modified_at: 2023-07-06
---

Nitrogen-vacancy (NV) centres have presented unique features in the world of quantum physics, especially in terms of their spin relaxation decay time, or $T_1$. Under regular conditions, this decay time is confined to approximately 5 milliseconds. Remarkably, when subjected to a low-temperature environment, it extends to an impressive 3,600 seconds, with cross-relaxation effects becoming negligible.

The experimentally determined $T_1$ times have demonstrated the capacity to outstrip limitations that are theoretically rooted in single-phonon processes$^{[1]}.$ This counterintuitive phenomenon suggests an incomplete understanding of the specific dynamics between spin and phonon interactions.

The application of dynamical decoupling sequences shows promise in augmenting the coherence times of the electron spin, represented by $T^{*}_2$ and $T_2$. By deploying these sequences, it's possible to maintain an arbitrary quantum state for periods exceeding 1 second. The prolonged coherence time becomes instrumental when attempting to probe spins that are weakly coupled within the local spin environment.

The structure of the diamond lattice lends itself to the manipulation of entangled states of multiple qubits. It achieves this by using nuclear spins as an integral resource. The comprehensive spin-system comprises the electron and nuclear spins of the NV centre, along with the neighbouring $^{13}C$ nuclear spins.

The system Hamiltonian encapsulates the total energy of this spin system. 

$$
H_{sys} = H_e + H_N + H_{e-N} + H_C + H_{e-C} + H_{C-C} + H_{N-C}
$$

It can be dissected into individual spin species and the interactions occurring between each pair. The Hamiltonian variables for electron, nitrogen, and carbon spins are represented by $H_e$, $H_N$, and $H_C$ respectively. Meanwhile, the term $H_{i-j}$ signifies the interactions happening pairwise. The nitrogen spin and its interaction with the electron spin is

$$

\begin{aligned}

H_N &= - Q I^2_{z,N} + \gamma_N(\textbf{B} \cdot \textbf{I}_N) \\
H_{e-N} &= \textbf{S} \cdot \textbf{A}_N \cdot \textbf{I}_N \approx A_{\parallel,N} S_Z I_{z,N}

\end{aligned}

$$


The hyperfine tensor, signifying the interaction between the electron and nitrogen, is denoted by $A_N$. Within this, the ZZ coupling is represented as $A_{\parallel,N}$. Each $^{13}C$ spin has its distinctive interaction with the electron, made up of both dipole-dipole and Fermi contact terms. The Hamiltonian terms for the $^{13}C$ spins and their interaction with the electron are given by

$$

\begin{aligned}

H_C &= \sum_i \gamma_C (\textbf{B} \cdot \textbf{I}_C^{(i)}) \\
H_{e-C} &= \sum_i \textbf{S} \cdot \textbf{A}_C^{(i)} \approx \sum_i (A_{\parallel,C}^{(i)} S_z I_{z,C}^{(i)} + A_{\perp, C}^{(i)} S_z I_{x, C}^{(i)})

\end{aligned}

$$

Each $^{13}C$ spin also possesses a unique coordinate system. This is determined by the spatial orientation of its hyperfine interaction. Specifically, the hyperfine component that is perpendicular to the NV-axis, $A^{(i)}_{\perp,C}$, operates along the x-axis of the given $^{13}C$ spin.

We also have dipolar interactions betewen nuclear spins

$$
\begin{aligned}

H_{C-C} &= \sum_{i,j} \textbf{I}_C^{(i)} \cdot \textbf{C}_{i-j} \cdot \textbf{I}_C^{(j)} \\
H_{N-C} &= \sum_i \textbf{I}_N \cdot \textbf{C}_{N-j} \cdot \textbf{I}_C^{(i)}

\end{aligned}
$$

$\textbf{C}_{i-j}$ and $\textbf{C} _{N-j}$ are the $ ^{13}C - ^{13}C $ and $ ^{14}N - ^{13}C $ interactions tensors.

Electron-nuclear couplings typically showcase strength that is 3-4 orders of magnitude higher than that of nuclear-nuclear couplings. This disparity is primarily due to differences in their gyromagnetic ratios. As a result, the effective nuclear-nuclear interaction strengths undergo modifications.





**<U>Reference</U>**

1. Bradley, C. E. Order from Disorder: Control of Multi-Qubit Spin Registers in Diamond. (2021).