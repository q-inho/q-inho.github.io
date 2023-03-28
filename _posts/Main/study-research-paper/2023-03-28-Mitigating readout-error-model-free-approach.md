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

If there are no readout errors, the measurement output of \\(n\\) qubits can be represented by a probability distribution \\(p\\) over the \\(2^n\\) computational basis states. A classical noise map \\(A\\) is typically used to model readout errors, which maps the noise-free probability distribution \\(p\\) to a noisy distribution \\(\tilde{p}=Ap\\). The readout map \\(A\\) is a left-stochastic matrix with dimensions of \\(2^n\times2^n\\), where the element \\(A_{i,j}\\) represents the probability of measuring the \\(i\\)th computational basis state instead of the \\(j\\)th computational basis state, for \\(i,j\in{0,1}^n\\). For example, if \\(n=2\\), there are four possible computational basis states: \\(\|00\rangle\\), \\(\|01\rangle\\), \\(\|10\rangle\\), and \\(\|11\rangle\\). The element \\(A_{00,01}\\) denotes the probability of measuring \\(\|00\rangle\\) but incorrectly reading it as \\(\|01\rangle\\). Similarly, \\(A_{10,11}\\) represents the probability of measuring \\(\|10\rangle\\) but incorrectly reading it as \\(\|11\rangle\\).

>**Left-stochastic matrix**
>
>A left-stochastic matrix is a square matrix where each row sums to one and all its entries are non-negative. In other words, it is a matrix where the entries represent probabilities of transitioning from one state to another, and the sum of probabilities for each row is equal to one. In quantum computing, left-stochastic matrices can be used to model noise in quantum circuits, such as depolarizing noise or readout errors.
>An example of a left-stochastic matrix is:
>
>$$
\begin{pmatrix}
0.4 & 0.3 & 0.3 \\
0.2 & 0.5 & 0.3 \\
0.1 & 0.2 & 0.7 \\
\end{pmatrix}
$$
>
>In this matrix, each row sums to one, and all entries are non-negative probabilities of transitioning from one state to another. For example, the entry in the first row and second column represents the probability of transitioning from state 1 to state 2, which is 0.3 in this case.


A common method to mitigate the impact of readout errors involves estimating the columns of the readout map \\(A\\) by measuring the output frequencies \\(\hat{r}_x\\) for different bit strings \\(x\\), and then applying the matrix \\(A^{-1}\\) for correction. To elaborate, we perform measurements on a quantum system and keep track of the frequency with which each computational basis state is observed. These frequency measurements enable us to estimate the columns of the readout map \\(A\\), which describe the likelihood of measuring each computational basis state correctly or incorrectly due to readout errors. Once we have obtained these column estimates, we can invert the matrix \\(A\\) using its inverse \\(A^{-1}\\) to correct for the errors.

The inverse of a matrix reverses its impact on vectors, so applying \\(A^{-1}\\) after measuring a vector corrects any errors introduced by \\(A\\). In this context, applying \\(A^{-1}\\) after measuring a quantum state corrects for any readout errors that may have occurred during the measurement process.

> **Example**
>Suppose we have a quantum system with two qubits, and we want to measure the expectation value of the Pauli observable \\(Z_1 \cdot Z_2\\) (i.e., the product of the \\(Z\\) Pauli matrices on qubits 1 and 2). To do this, we first prepare the system in some initial state (e.g., \\(\|00\rangle\\)), then apply a quantum circuit that implements the desired operation (in this case, a CNOT gate followed by two Hadamard gates). After applying the circuit, we measure the system in the computational basis and record the frequency with which each computational basis state is observed. Suppose we obtain the following measurement results:
>
> \\(\|00\rangle\\): 1000 counts
>
>\\(\|01\rangle\\): 200 counts
>
>\\(\|10\rangle\\): 150 counts
>
>\\(\|11\rangle\\): 650 counts
>
>Using these frequency measurements, we can estimate the columns of the readout map \\(A\\). For example, to estimate column 1 of \\(A\\) (which corresponds to measuring \\(\|00\rangle\\)), we would divide the number of counts for \\(\|00\rangle\\) by the total number of counts:
>
>\\(A_{1,1} = 1000 / (1000 + 200 + 150 + 650) = 0.571\\)
>
>Similarly, to estimate column 2 of \\(A\\) (which corresponds to measuring \\(\|01\rangle\\)), we would divide the number of counts for \\(\|01\rangle\\) by the total number of counts:
>
\\(A_{2,1} = 200 / (1000 + 200 + 150 + 650) = 0.114\\)
>
>We can repeat this process for all four columns of \\(A\\) to obtain estimates for each entry.
>
>Once we have estimated these columns, we can invert \\(A\\) using its inverse \\(A^{-1}\\) to correct for readout errors. In this case, since \\(A\\) is a left-stochastic matrix, its inverse is also left-stochastic, so we can simply apply \\(A^{-1}\\) to the measurement results to correct for errors. For example, suppose we measured the state \\(\|01\rangle\\) but incorrectly read it as \\(\|00\rangle\\). To correct for this error, we would apply the first column of \\(A^{-1}\\) (which corresponds to measuring \\(\|00\rangle\\)) to the measurement result:
>
>\\(A^{-1} \cdot \begin{bmatrix}1 \ 0 \ 0 \ 0\end{bmatrix} = \begin{bmatrix}0.571 \ -0.114 \ -0.086 \ -0.371\end{bmatrix}\\)
>
>The corrected measurement result is then given by the probabilities in the resulting vector, which sum to 1. In this case, we can see that the corrected probability of measuring \\(\|01\rangle\\) is:
>
>\\(\|01\rangle\\): \\(0.114 / (0.571 - 0.114 - 0.086 - 0.371) = 0.25\\)
>
>This corrected probability is higher than the original probability of measuring \\(\|01\rangle\\), which was only \\(200 / (1000 + 200 + 150 + 650) = 0.114\\). By correcting for readout errors using \\(A^{-1}\\), we can obtain more accurate measurement results and improve the overall performance of our quantum system.

Explicitly representing and inverting the readout map \\(A\\) is only feasible for small system sizes or when the noise can be assumed to factorize, such that noise on individual or small groups of qubits can be modeled and inverted independently. The readout map \\(A\\) is a \\(2^n \times 2^n\\) matrix, where \\(n\\) is the number of qubits in the quantum system. As \\(n\\) increases, the size of \\(A\\) grows exponentially, making it increasingly difficult to represent and invert explicitly. For example, if we have a system with just 10 qubits, then \\(A\\) will be a \\(1024 \times 1024\\) matrix. If we have a system with 20 qubits, then \\(A\\) will be a \\(1,048,576 \times 1,048,576\\) matrix. In general, the size of \\(A\\) grows as \\(2^{2n}\\), which quickly becomes infeasible to work with for large values of \\(n\\).

Furthermore, the readout map \\(A\\) is a tensor product of individual qubit readout maps, so noise is assumed to factorize. In other words, the probability of measuring a particular bit string in the computational basis depends only on the probabilities of measuring each qubit in that bit string independently. This means that if we can model and invert the noise on each qubit independently, then we can also model and invert the noise on the entire system. For example, suppose we have a system with two qubits, and we want to measure the expectation value of the Pauli observable \\(Z_1 \cdot Z_2\\). If we assume that noise on each qubit is independent and identically distributed, then we can model each qubit's readout error using a single-qubit readout map \\(A_i\\) for \\(i=1,2\\). The overall readout map \\(A\\) for the two-qubit system is then given by \\(A = A_1 \otimes A_2\\), where \\(\otimes\\) denotes the tensor product. We can estimate columns of \\(A\\) by measuring output frequencies for different bit strings as described earlier and then apply its inverse to correct for readout errors.

However, if noise does not factorize in this way (e.g., if there are correlations between errors on different qubits), then modeling and inverting noise becomes much more difficult.

Experiments have revealed that noise tends to be correlated, making the use of product approximations to the stochastic matrix unreliable. A recent blog post describes a readout-error-mitigation method that can handle correlated noise, with a formal guarantee of performance based on the strength of the noise. This method was both proposed and experimentally implemented in the blog post. It avoids the need to explicitly invert the noise map, and the model can be represented concisely using \\(O(poly(n))\\) parameters.

The twirled-readout method is a technique that adds uniform random Pauli bit flips prior to measurement to randomize the output channel. This randomness can help counteract biases caused by hardware imperfections by effectively "averaging out" these biases. The random bit flips are tracked and used in subsequent analysis to correct for these biases and obtain more accurate measurements. The Pauli bit flips transform the effect of any arbitrary noise map into a single multiplicative factor per Pauli observable, which diagonalizes the measurement channel and simplifies bias correction. The method can be applied to a wide range of quantum systems beyond single-qubit models, and it requires no prior assumptions or models of the readout-error process other than the ability to initialize the circuit in the zero state. The shot-noise variance of the mitigated estimate is inversely proportional to the magnitude of the noise factor, and the necessary number of measurement samples for a desired estimation accuracy can be analyzed based on the underlying noise strength.

##### References
- van den Berg, E., Minev, Z. K. &amp; Temme, K. Model-free readout-error mitigation for quantum expectation values. Physical Review A 105, (2022). 