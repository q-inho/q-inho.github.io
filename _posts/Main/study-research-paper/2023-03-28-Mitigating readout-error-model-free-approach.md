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
Quantum algorithms for near-term devices involve executing a shallow quantum circuit followed by measurement of an observable through sampling. However, hardware noise can cause errors in quantum computations, leading to biased expectation values. To mitigate errors, error-mitigation techniques have been introduced, including schemes to correct readout errors that occur during the final measurement step of the computation. In this work, the researcher focuses on the mitigation of readout errors when computing the expectation values of Pauli observables. Pauli matrices constitute a Hermitian matrix basis, which means they can represent any observable, and any observable that can be expanded in a polynomial number of Pauli matrices can be estimated efficiently by measuring the expectation values of Pauli observables.

After applying a quantum circuit, we can measure a Pauli observable, rotate it to the computational basis using single-qubit Clifford gates, and measure the qubits in the computational basis. We can then obtain an estimate of the expectation value of the Pauli observable using some basic classical postprocessing techniques. The readout map \\(A\\) is a \\(2^n\times2^n\\) left-stochastic matrix that describes how likely it is for each computational basis state to be measured correctly or incorrectly due to readout errors. To correct for readout errors, we can estimate the columns of A by measuring the output frequencies for different bit strings and then apply its inverse \\(A^(-1)\\).

However, explicitly representing and inverting A becomes increasingly difficult for large numbers of qubits. The readout map A is a tensor product of individual qubit readout maps, and noise is assumed to factorize. If noise does not factorize, modeling and inverting noise becomes much more difficult. Recent experiments have shown that noise tends to be correlated, which invalidates the use of product approximations to the stochastic matrix.

A readout-error-mitigation scheme for correlated noise has been proposed and implemented experimentally, which does not require explicit inversion of the noise map and can be concisely represented using O(poly(n)) parameters. The twirled-readout method randomizes the output channel by uniformly applying random Pauli bit flips prior to measurement, which can correct for any biases caused by hardware imperfections. The method makes only the assumption that the circuit can be initialized in the zero state and can be applied to a wide range of quantum systems beyond single-qubit models. The shot-noise variance of the mitigated estimate scales inversely proportional to the magnitude of the noise factor, and the required number of measurement samples to attain a desired estimation accuracy can be analyzed based on the underlying noise strength.


##### References
- van den Berg, E., Minev, Z. K. &amp; Temme, K. Model-free readout-error mitigation for quantum expectation values. Physical Review A 105, (2022). 