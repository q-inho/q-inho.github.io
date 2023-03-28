---
title:  "Mitigating Readout Errors: A Model-Free Approach"
excerpt: "In the paper, 'Model-free readout-error mitigation for quantum expectation values,' Ewout van den Berg, Zlatko K. Minev, and Kristan Temme propose a new approach to mitigating these errors using the twirled-readout method."

categories:
  - Study/Research/Paper
tags:
  - [Quantum Computing, Error mitigation]

toc: true
toc_sticky: true
 
date: 2023-03-28
last_modified_at: 2023-03-28
---
# Background
The execution of quantum algorithms on near-term devices often involves a shallow quantum circuit that is followed by sampling the measurement of an observable. When the circuit is executed, the output is a superposition of several possible states, and measuring an observable collapses this superposition into a single state. By repeating this process multiple times and gathering statistics on the outcomes, we can estimate the expectation value of the observable. This method is preferred for near-term devices because proper quantum error correction is not yet available, and noise parameters such as coherence time limit the depth of the circuit and thus determine the scale of the computation that can be carried out. The noise can cause errors in quantum computations by causing qubits to lose their quantum state and become entangled with other qubits or the environment, a process known as decoherence. Hardware noise can introduce a bias that affects expectation values, even when working within these restrictions. Error-mitigation techniques have been developed to remove this bias and produce more accurate expectation values. However, these techniques come at a cost, such as repeating the computation with modified parameters, increased sampling costs, or additional classical postprocessing. Several schemes have been proposed and experimentally implemented to mitigate errors that occur during the application of the quantum circuit.

In this study, the author investigates the reduction of readout errors that arise during the final measurement phase of a computation. They specifically concentrate on calculating the expectation values of Pauli observables, which are a set of matrices that can represent any observable due to their Hermitian properties. Additionally, any observable that can be expressed as a polynomial combination of Pauli matrices, including local Hamiltonians, can be efficiently estimated by measuring the expectation values of Pauli observables due to the expectation value's linearity.

> **Hermitian matrices**
>
>These are a special type of matrix that have the property that their transpose is equal to their complex conjugate. In quantum mechanics, observables are represented by Hermitian operators, which are matrices that satisfy this property. Pauli matrices are a set of three \\(2\times 2\\) Hermitian matrices that are commonly used in quantum mechanics to represent spin states and other physical quantities. Any observable can be expressed as a linear combination of these Pauli matrices, which means that they form a complete basis for the space of \\(2\times2\\) Hermitian matrices. Therefore, by measuring the expectation values of Pauli observables, we can estimate the expectation values of any observable in an efficient manner due to the linearity of the expectation value.


##### References
- van den Berg, E., Minev, Z. K. &amp; Temme, K. Model-free readout-error mitigation for quantum expectation values. Physical Review A 105, (2022). 