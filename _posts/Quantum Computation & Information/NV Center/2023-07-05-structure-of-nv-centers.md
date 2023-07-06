---
title: "Complex Optical Properties and Fine Structure of NV Centres"
excerpt: "This examination elucidates the complex molecular orbital structure of NV centres, the external influences on their energy transitions, the methodical control of spin initialization and readout, and the critical role of readout fidelity, offering substantial insights for advancing quantum applications."

header:
  overlay_image: 
  overlay_filter: 

categories:
  - NV Center
tags:
  - [Quantum Computing]

toc: true
toc_sticky: true
 
date: 2023-07-05
last_modified_at: 2023-07-05
---

The Nitrogen-Vacancy (NV) center in a diamond is an intriguing model, demonstrating a unique arrangement of molecular orbitals. These orbitals emerge from the neighboring elements of nitrogen and carbon. In their most stable or ground state, these centers boast two fully occupied orbitals, accompanied by two degenerate orbitals. Each of these hosts a single unpaired electron, adding to the complexity and richness of the NV center's ground state.

A captivating feature of the NV center is its optical transition between the ground state and the first-excited states. This phenomenon does not lead to charge transfer between the NV center and the diamond lattice. This intriguing characteristic renders its optical properties analogous to a trapped ion within a vacuum, presenting an interesting juxtaposition of a robust diamond structure and the isolated nature of vacuum-trapped ions.

The NV center’s energy states and permissible transitions are meticulously mapped out in Figure 1. The external magnetic field uniquely breaks the degeneracy of the ground state levels marked by ms = $\pm 1$. This critical event paves the way to access isolated qubit states, enabling high-precision studies and manipulation of the NV center.

<p align="center">
  <img width="610" src="https://github.com/q-inho/q-inho.github.io/assets/79438062/f36c0d4f-bbbf-4c79-ba19-6e1151d3e91f">
<br> <b>Figure 1. Level structure of the NV$^−$ centre in diamond </b>. Source: (Bradley)$^{[1]}$
</p>

The ground-state electronic Hamiltonian is

$$

H_e = \Delta_{ZFS} S_z^2 + \gamma_e(\textbf{B} \cdot \textbf{S})

$$


Leveraging microwave driving at the relevant transition frequency is a remarkable approach for manipulating the ground-state qubit. This technique empowers researchers to achieve high-fidelity qubit manipulation within tens of nanoseconds, underlining the efficiency and precision of this method.

Optical excitation aids the transitions to six distinct spin-triplet orbital-doublet first-excited states. These transitions can be distinctly resolved at cryogenic temperatures, offering a comprehensive window into the NV center's complex and dynamic nature.

A particular series of transitions present a highly effective method for spin initialization and readout. Astonishingly, these transitions can attain readout fidelities surpassing 99.7% within an incredibly short span of just 3 microseconds.

Through the excitation of selected subsets such as A$_1$, E$_1$, and E$_2$, it is possible to achieve 'spin-pumping' into the $m_s = 0$ state. This strategy leads to a rapid and precise spin initialization, further enhancing our understanding and control of these NV centers.

The Inter-system Crossing (ISC) rates from states such as A$_2$, E$_x$, and E$_y$ are lowered. Moreover, exciting the $m_s=0$ ground state on either the $E_x$ or $E_y$ transition results in a highly cyclical behavior, enabling single-shot read-out. The quality of the read-out process is described by the single-shot read-out fidelity.

$$

F_{SSRO} = \frac{1}{2}(F_{0 | 0} + F_{1 | 1})

$$

where $F_{i\vert j}$ is the probability to assign the state $\vert i \rangle$ after attempting initialization in the state $\vert j \rangle$.

This method can achieve a high fidelity of 94.3%, and implementing probabilistic measurements can further enhance the quality of specific operations.

When it comes to selecting optical transitions, spectral isolation and read-out cyclicity are of paramount importance. Typically, the Ex transition is favored, given its unique characteristics and its potential contribution to the expanding field of NV center studies.

**<U>Reference</U>**

1. Bradley, C. E. Order from Disorder: Control of Multi-Qubit Spin Registers in Diamond. (2021).