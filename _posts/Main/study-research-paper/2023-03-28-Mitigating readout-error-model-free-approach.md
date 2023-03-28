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
>
>After a quantum circuit has been applied, we can measure a Pauli observable. This is done by rotation of the observable to the computational basis using single-qubit Clifford gates, followed by measurement in this basis and some basic classical postprocessing. The process involves the following steps:
>
>1. Choose a Pauli observable to measure.
>2. Apply single-qubit Clifford gates to rotate the Pauli observable to the computational basis.
>3. Measure the qubits in the computational basis.
>4. Perform some basic classical postprocessing on the measurement results to obtain an estimate of the expectation value of the Pauli observable.
>
>The single-qubit Clifford gates used in step 2 are a specific set of quantum gates that can be used to transform any Pauli observable into another Pauli observable or into the identity matrix. These gates are important because they allow us to perform measurements in a standard basis, which is easier to implement experimentally than measurements in other bases. After measuring the qubits in step 3, we obtain a string of 0s and 1s that corresponds to a particular computational basis state. By repeating this process many times and averaging over the results, we can estimate the probability distribution over all possible computational basis states. From this probability distribution, we can compute an estimate of the expectation value of the Pauli observable using some basic classical postprocessing techniques.

If there are no readout errors, the measurement output of $n$ qubits can be represented by a probability distribution \\(p\\) over the \\(2^n\\) computational basis states. A classical noise map \\(A\\) is typically used to model readout errors, which maps the noise-free probability distribution $p$ to a noisy distribution \\(\tilde{p}=Ap\\). The readout map \\(A\\) is a left-stochastic matrix with dimensions of \\(2^n\times2^n\\), where the element \\(A_{i,j}\\) represents the probability of measuring the \\(i\\)th computational basis state instead of the \\(j\\)th computational basis state, for \\(i,j\in{0,1}^n\\). For example, if \\(n=2\\), there are four possible computational basis states: \\(\|00\rangle\\), \\(\|01\rangle\\), \\(\|10\rangle\\), and \\(\|11\rangle\\). The element \\(A_{00,01}\\) denotes the probability of measuring \\(\|00\rangle\\) but incorrectly reading it as \\(\|01\rangle\\). Similarly, \\(A_{10,11}\\) represents the probability of measuring \\(\|10\rangle\\) but incorrectly reading it as \\(\|11\rangle\\).

>**Left-stochastic matrix**
>
>A left-stochastic matrix is a square matrix where each row sums to one and all its entries are non-negative. In other words, it is a matrix where the entries represent probabilities of transitioning from one state to another, and the sum of probabilities for each row is equal to one. In quantum computing, left-stochastic matrices can be used to model noise in quantum circuits, such as depolarizing noise or readout errors.
>An example of a left-stochastic matrix is:
>$$
\begin{pmatrix}
0.4 & 0.3 & 0.3 \\
0.2 & 0.5 & 0.3 \\
0.1 & 0.2 & 0.7 \\
\end{pmatrix}
$$
In this matrix, each row sums to one, and all entries are non-negative probabilities of transitioning from one state to another. For example, the entry in the first row and second column represents the probability of transitioning from state 1 to state 2, which is 0.3 in this case.


A common method to mitigate the impact of readout errors involves estimating the columns of the readout map $A$ by measuring the output frequencies \\(\hat{r}_x\\) for different bit strings \\(x\\), and then applying the matrix \\(A^{-1}\\) for correction. To elaborate, we perform measurements on a quantum system and keep track of the frequency with which each computational basis state is observed. These frequency measurements enable us to estimate the columns of the readout map \\(A\\), which describe the likelihood of measuring each computational basis state correctly or incorrectly due to readout errors. Once we have obtained these column estimates, we can invert the matrix \\(A\\) using its inverse \\(A^{-1}\\) to correct for the errors.

The inverse of a matrix reverses its impact on vectors, so applying \\(A^{-1}\\) after measuring a vector corrects any errors introduced by \\(A\\). In this context, applying \\(A^{-1}\\) after measuring a quantum state corrects for any readout errors that may have occurred during the measurement process.

##### References
- van den Berg, E., Minev, Z. K. &amp; Temme, K. Model-free readout-error mitigation for quantum expectation values. Physical Review A 105, (2022). 