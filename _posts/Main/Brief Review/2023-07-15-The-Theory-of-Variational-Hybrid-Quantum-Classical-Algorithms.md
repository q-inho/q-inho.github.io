---
title: "Brief Reviews on The Theory of Variational Hybrid Quantum-Classical Algorithms"
excerpt: ""

header:
  overlay_image: 
  overlay_filter: 

categories:
  - Brief Review
tags:
  - [Quantum Chemistry, Quantum Algorithm]

toc: true
toc_sticky: true
 
date: 2023-07-15
last_modified_at: 2023-07-15
---

This review is written by **non-expert** and used for **personal** study only. This post content is continuously improving.
{: .notice--danger}

At the confluence of computation and quantum physics lies the potential to **revolutionize problem-solving across diverse fields**. Harnessing this potential, quantum computers have been demonstrated to exponentially accelerate solutions to eigenvalue and optimization problems, areas of significant importance in a multitude of applications.

Distinguished amongst quantum algorithms, the **Variational Quantum Eigensolver (VQE)** stands as a robust hybrid of quantum and classical computations. Its prowess lies in its capability to uncover solutions for eigenvalue and optimization issues that are far beyond the reach of conventional classical computers. Inherently adaptable, VQE exhibits versatility by working seamlessly with any quantum device. Moreover, its ability to suppress specific quantum errors variationally renders it a potent contender for outpacing classical computers.

The **VQE algorithm's proficiency has seen a surge through both theoretical and experimental extensions**. Coupled with the application of contemporary derivative-free optimization methodologies, the efficacy of VQE is dramatically amplified.

To comprehend the scope of VQE's functionality, we examine a quantum system of N qubits paired with a Hamiltonian $\mathcal{H}$. This system provides valuable insights into the Hamiltonian's eigenvectors and eigenvalues, shedding light on physical systems or optimization challenges.

Eigenvectors within the VQE framework are encoded via parameters, with the emphasis on **low-energy states** that hold prime significance in both physical systems and optimization problems.

The expectation value of an operator $\mathcal{O}$ corresponding to a state can be efficiently gauged on a quantum device and transferred to a quantum state, given the operator's decomposable nature into a polynomial sum of simpler operators.

$$

\langle \mathcal{O} \rangle _{\vert\Psi \rangle} = \frac{\langle \Psi \vert \mathcal{O} \vert \Psi \rangle}{\langle \Psi \vert \Psi \rangle}

$$

The ideal selection of parameters for approximating a Hamiltonian $\mathcal{H}$'s ground state is one that minimizes the energy expectation value, while state normalization is ensured by the inherent properties of quantum evolution or trace preservation during quantum operations.

$$

\langle \mathcal{H} \rangle_{\rho (\overrightarrow{\theta})} \equiv \langle \mathcal{H} \rangle (\overrightarrow{\theta}) = \text{Tr}[\rho (\overrightarrow{\theta}) \mathcal{H}] \geq \lambda_1

$$

The **folded spectrum technique** proves useful in identifying excited states by minimizing the altered Hamiltonian. Remarkably, the ground state variational principle continues to be applicable for mixed states, thereby enabling error suppression without explicit knowledge of the error's source.

Recently, **quantum chemistry and fermionic Hamiltonians** have garnered interest due to the VQE's principles. The electronic structure problem, which necessitates solving for eigenvectors and eigenvalues of the electronic Hamiltonian, becomes achievable. A second quantized Hamiltonian is obtained through the problem's projection onto a finite, orthogonal, spin-orbital basis, alongside the imposition of fermion anti-symmetry.

$$
H = \sum_{pq} h_{pq} a_p^\dagger a_q + \frac{1}{2}\sum_{pqrs} h_{pqrs} a_p^\dagger a_q^\dagger a_r a_s

$$

The transition from fermions to qubits becomes critical when resolving these problems on quantum computers. Amongst popular mappings, the **Jordan-Wigner transformation** takes precedence. Traditional electronic structure methodologies, on the other hand, leverage a reference state to define an expanded quantum state, simplifying formal operations.

Although multi-reference methods present theoretical and computational challenges in quantum chemistry, their generalization on quantum computers often emerges more naturally than in classical scenarios.

The variational methodology algorithm in a quantum computer prepares a state, measures the expectation value, determines new parameter values through a classical nonlinear optimizer, and iterates until energy value convergence is reached.

Once a state is prepared, its proximity to the solution can be determined using standard distribution approximation and Weinstein inequalities.

The concept of **adiabatic state preparation**, specifically with a varying path, introduces a unique type of quantum state as a parametric ansatz. In this case, the optimal path is the one that minimizes the energy expectation value.

The **unitary coupled cluster method** provides an avenue for exploring the Hilbert space of potential quantum states, using spin-flip operators to parameterize all states within this space.

Specialized for quantum chemistry and fermionic problems, the **Fermionic UCC method** builds cluster operators that conserve particle number and rely on real parameters.

The essential step of operator averaging in the VQE algorithm aids in evaluating the objective function corresponding to the problem operator H. Hamiltonian averaging retains the advantage of preparing classically inaccessible states while eliminating excessive coherence time requirements for energy measurement.

Two main strategies are proposed to reduce Hamiltonian averaging's computational cost: **term truncation**, which involves eliminating less significant terms, and **commuting groups**, which group commuting operators to reduce necessary state preparations.

The VQE method updates parameters based on the measured objective function, which is nonlinear and non-convex. The method of calculating operator averages can deliver additional information apart from the original expectation value. These insights, combined with reduced density matrix knowledge, can unravel the nature of the quantum algorithm.

Despite quantum computers' transformative potential, technical hurdles persist in the development of error-corrected devices. **Variational algorithms such as VQE may herald the quantum edge over classical supercomputers** for practical problem-solving. As the dimension of problem space increases, further numerical testing is essential, and ongoing research is focused on enhancing the algorithm's runtime, ushering in a new era of quantum computation.

**<U>Reference</U>**

1. McClean, J. R., Romero, J., Babbush, R. &amp; Aspuru-Guzik, A. The theory of variational hybrid quantum-classical algorithms. New Journal of Physics 18, 023023 (2016). 