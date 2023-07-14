---
title: "Brief Reviews on A Variational Eigenvalue Solver on a Photonic Quantum Processor"
excerpt: ""

header:
  overlay_image: 
  overlay_filter: 

categories:
  - Brief Review
tags:
  - [Quantum Optics, Quantum Chemistry, Applied Physics]

toc: true
toc_sticky: true
 
date: 2023-07-14
last_modified_at: 2023-07-14
---

This review is written by **non-expert** and used for **personal** study only. This post content is continuously improving.
{: .notice--danger}

The process of determining the characteristics of atoms and molecules through the resolution of the Schrödinger equation is traditionally unattainable for compounds composed of more than a couple of atoms. Quantum computation offers an innovative approach to solve many instances of large eigenvalue problems that are insurmountable through classical means.

Quantum computation has seen the advent of an alternate method to Quantum Phase Estimation (QPE). This innovative method, leveraging a reconfigurable Quantum Processing Unit (QPU) and a variational algorithm, significantly diminishes the need for coherent evolution. This novel approach, known as Quantum Expectation Estimation (QEE), enables the computation of the expectation value of a particular Hamiltonian $\mathcal{H}$ for a certain input state. Any Hamiltonian for real $h$ is

$$

\mathcal{H} = \sum_{i \alpha} h_\alpha^i \sigma_\alpha^i + \sum_{i j \alpha \beta} h_{\alpha \beta}^{ij} \sigma_\alpha^i \sigma_\beta^j + ...
$$

Without any assumptions about the dimension or structure of the hermitian Hamiltonian, it's possible to represent any Hamiltonian, while identifying subsystems and the Pauli operator respectively with Roman and Greek indices. Utilizing the principle of linearity in quantum observables, this complex procedure can be transformed into a manageable task. By linearity of quantum observables it is

$$

\langle \mathcal{H} \rangle = \sum_{i \alpha} h_\alpha^i \langle \sigma_\alpha^i \rangle + \sum_{i j \alpha \beta} h_{\alpha \beta}^{ij} \langle \sigma_\alpha^i \sigma_\beta^j \rangle + ...

$$

Hamiltonians that can be expressed as a polynomial number of terms relative to the system size cover a broad spectrum of physical systems. This expansive scope includes the electronic structure Hamiltonian of quantum chemistry, the quantum Ising Model, the Heisenberg Model, matrices that closely approximate a sum of n-fold tensor products, and any k-sparse Hamiltonian devoid of evident tensor product structure.

By simplifying the evaluation of these Hamiltonians into the sum of a polynomial number of expectation values of uncomplicated Pauli operators for a quantum state, and multiplying these by certain real constants, a quantum device can assess the expectation value of a tensor product of an arbitrary number of simple Pauli operators in an efficient manner.

Quantum hardware possesses the distinct advantage of storing a global quantum state with significantly fewer resources than classical hardware, successfully bypassing the N-representability issue. The Quantum Variational Eigensolver (QVE) algorithm emerges as a variational method that supersedes the prolonged coherent evolution demanded by QPE, opting instead for several brief coherent evolutions. This method requires a short coherent evolution for the preparation of the eigenstate.

Recognized universally, the eigenvalue problem for an observable depicted by operator H can be restated as a variational problem on the Rayleigh-Ritz quotient. Through varying experimental parameters in the preparation of a certain quantum state and computing the Rayleigh-Ritz quotient using QEE as a sub-procedure in a classical minimization, one can prepare unknown eigenvectors. We have successfully implemented the QPU using integrated quantum photonics technology, which prepares and measures arbitrary two-bit pure states through single-qubit rotations and one two-qubit entangling gate.

Quantum Expectation Estimation (QEE) showcases the potential for using fewer quantum resources than QPE, thereby reducing the strain on components and coherence time. With QVE, there's a fresh approach to device construction, delivering a variationally optimal solution with the given quantum resources.


**<U>Reference</U>**

1. Peruzzo, A. et al. A variational eigenvalue solver on a photonic quantum processor. Nature Communications 5, (2014). 