---
title: "[Brief Review] Nature, Volume 616 Issue 7955, 6 April 2023"
excerpt: "Brief Review on 'Real-time quantum error correction beyond break-even', 'Beating the break-even point with a discrete-variable-encoded logical qubit', 'Gate-tunable heavy fermions in a moire Kondo lattice', '2D fin field-effect transistors integrated with epitaxial high-k gate oxide', 'Deforming lanthanum trihydride for superionic conduction', and 'A LaCl3-based lithium superionic conductor compatible with lithium metal' "


categories:
  - Study/Research/Paper
tags:
  - [Quantum Information]

toc: true
toc_sticky: true
 
date: 2023-04-05
last_modified_at: 2023-04-06
---

This review is written by **non-expert** and used for **personal** study only.
{: .notice--danger}

# Real-time quantum error correction beyond break-even
- **<U>Quantum Information</U>**

Creating a reliable logical qubit requires a physical system with a vast state space and redundancy. This design ensures that logical information can be accurately transferred without distortion, even when physical errors occur. Bosonic codes, derived from a harmonic oscillator's state space, have emerged as a promising alternative to the conventional approach using registers of physical qubits. However, control overhead has hindered current experiments from achieving a coherence time gain ($G$) for actively error-corrected logical qubits compared to the best passive qubit encoding in the same system.

Researchers have made progress with full code stabilization and error correction of logical qubits using $GKP$ encoding. This process involves converting a logical qubit into an oscillator's grid states and implementing a 'trickle-down' quantum error correction (QEC) scheme based on prior research proposals. With low logical error probabilities and resulting lifetimes of logical Pauli eigenstates, this method has allowed the exploration of QEC processes on previously unattainable timescales.

> **GKP**
>
> GKP encoding works by mapping a logical qubit onto an infinite-dimensional Hilbert space spanned by the eigenstates of a harmonic oscillator. This encoding allows for continuous-variable quantum error correction, which means that it can correct errors in the amplitude and phase of the encoded state. 
>
> One advantage of GKP encoding is that it can be implemented using simple linear optics and homodyne detection techniques, which are relatively easy to implement experimentally. Additionally, GKP encoding has been shown to have high fidelity and coherence gain compared to other types of quantum error-correcting codes.

To efficiently eliminate entropy from the system, an artificial error-correcting dissipation was used. This method focuses on prioritizing the correction of frequent small errors while still addressing rare large errors. The strategy reduces control overhead in grid code and has been demonstrated in other bosonic codes as well.

> **Grid code**
>
> A grid code is used to protect quantum information from decoherence. In a grid code, a logical qubit is encoded into an infinite-dimensional Hilbert space spanned by the eigenstates of a harmonic oscillator. The code states are defined as superpositions of coherent states, which are displaced versions of the oscillator ground state. These coherent states are arranged in a grid-like pattern in phase space, with each point on the grid representing a different encoded state.
>
> Grid codes have several advantages over other types of quantum error-correcting codes. For example, they can be implemented using simple linear optics and homodyne detection techniques, which are relatively easy to implement experimentally. Additionally, they have been shown to have high fidelity and coherence gain compared to other types of quantum error-correcting codes.

> **Bosonic code**
>
> In a bosonic code, a logical qubit is encoded into a collection of bosonic modes. The code states are defined as superpositions of Fock states, which represent different numbers of photons in each mode. These Fock states are arranged in a specific pattern that allows for error correction and detection.
>
> Bosonic codes have several advantages over other types of quantum error-correcting codes. For example, they can be implemented using simple linear optics and photon counting techniques, which are relatively easy to implement experimentally. Additionally, they have been shown to have high fidelity and coherence gain compared to other types of quantum error-correcting codes

Researchers have constructed a rank-4 error correction channel using a single auxiliary qubit and classical controller. This is accomplished by implementing two rank-2 dissipators that guide the system towards the +1 eigenspace of the finite-energy code stabilizers. The dissipation channel implementation consists of qubit rotations, oscillator displacements, conditional rotations, and virtual oscillator rotations.

> **Rank**
>
> The rank of an error correction channel refers to the number of independent errors that can be corrected by the channel. In general, an error correction channel is a quantum operation that maps a noisy quantum state to a corrected quantum state. The goal of quantum error correction is to design channels that can correct errors caused by decoherence and other sources of noise.
>
> The rank of an error correction channel is an important parameter because it determines how many errors can be corrected by the channel. A higher rank means that more independent errors can be corrected, which leads to better performance in practice.

To enhance the performance of QEC, a real-time reinforcement learning (RL) agent is employed. The RL agent is trained using a logical Pauli eigenstate and a candidate QEC protocol, allowing it to find a QEC protocol that results in the longest logical qubit lifetime. The RL agent can learn the optimal value of the large intermediate displacement without a model, enhancing QEC performance at the expense of a considerably slower gate.

The best-performing QEC circuit is then selected for further analysis, emphasizing its capacity to create high-quality quantum memory. The average channel fidelity serves as a metric to quantify the deviation of any quantum channel from the identity.

Both types of qubits exhibit different fidelity decay rates due to amplitude damping and white-noise dephasing channels, with one type experiencing a higher fidelity decay constant. Grid states encoding for qubits incurs an immediate penalty in fidelity decay rate, eventually leading grid states away from the logical manifold and towards the vacuum state.

Error-correcting dissipation stabilizes the grid-code manifold, resulting in a logical Pauli channel with lifetimes of logical Pauli eigenstates. This leads to a coherence gain, confidently surpassing the break-even point.

The QEC process is investigated by measuring auxiliary qubit outcomes, known as **syndromes**, which offer insights into the stochastic path taken during each cycle. A simplified model of trickle-down dissipation is used to interpret the dataset, with the $g$ outcome indicating projection onto the code space and the $e$ outcome signifying partial or complete error correction. This dataset provides valuable information about the QEC process that was previously unattainable.

Real-time error correction has been utilized to create a stable logical qubit with a longer lifetime than passive qubit encoding, rendering QEC a practical tool for enhancing quantum memories. Challenges in grid-code QEC include occasional collapses of logical performance due to spurious degrees of freedom in the system. Future developments should incorporate robustness against auxiliary qubit bit flips, either through path-independent control or by adopting an auxiliary qubit with biased noise.

After initial state correction, the QEC process settles into a dynamic equilibrium that persists for at least a hundred thousand cycles without any significant increase in error rates over time. Residual deviations from stationarity are caused by transmon leakage to states higher than $\|f\rangle$ at a rate of $1.3 \times 10^{−4}$ per cycle.

Physical errors in the quantum state are prevented from accumulating and causing logical errors by low-rank error-correcting dissipation. The process successfully corrects $97%$ of errors. Rare large errors require several cycles to be corrected, resulting in a weakly time-correlated QEC process and lasting traces of outcomes generated by large-distance errors.

Post-selection of trajectories with different syndrome patterns can improve the fidelity lifetime of logical states in quantum computing. This method can eliminate both small and large errors, but with varying rejection probabilities per cycle.

Real-time error correction has been used to create a stable logical qubit with a longer lifetime than passive qubit encoding, making QEC a practical tool for enhancing quantum memories. Previous QEC experiments only protected certain Pauli operators and did not protect the logical identity operator $I_L$. Challenges in grid-code QEC include occasional collapses of logical performance due to spurious degrees of freedom in the system, which could be mitigated by adopting a tunable auxiliary qubit and periodically re-training the QEC circuit. As quantum computing advances, future development should focus on incorporating robustness against auxiliary qubit bit flips, either through path-independent control or by adopting an auxiliary qubit with biased noise. This will help to further improve the stability and reliability of logical qubits, paving the way for more advanced quantum technologies.

>**Required Additional Study Materials**
>
> - “Quantum Error Correction” by Daniel A. Lidar and Todd A
> - Joschka Roffe (2019) Quantum error correction: an introductory guide, Contemporary Physics, 60:3, 226-245, DOI: 10.1080/00107514.2019.1667078

**<U>Reference</U>**

Sivak, V.V., Eickbusch, A., Royer, B. et al. Real-time quantum error correction beyond break-even. [Nature 616, 50–55 (2023). ](https://doi.org/10.1038/s41586-023-05782-6)

-----

# Beating the break-even point with a discrete-variable-encoded logical qubit
- **<U>Quantum Information</U>**

Decoherence, which is the loss of quantum coherence, is a significant challenge in building quantum computers. However, quantum error correction (QEC) methods can help overcome this issue. Although QEC schemes have been shown to work in various systems, we need to increase the lifetime of logical qubits (the basic units of quantum information) to improve quantum information storage and processing. One promising approach for fault-tolerant quantum computation is using discrete-variable qubits encoded with mutually orthogonal **Fock states** (particular quantum states of an oscillator). However, increasing the lifetime of these encoded logical qubits remains a challenge.

> **Fock states**
>
>In quantum mechanics, a Fock state is a type of quantum state that describes the number of particles in a given mode of a quantum field. Specifically, a Fock state $\|n\rangle$ represents a state with exactly $n$ particles in the mode.
>
>Fock states are important in many areas of quantum physics, including quantum optics and quantum information processing. In particular, they are used to describe the states of photons in optical systems and the states of phonons in mechanical systems.
>
>In optical systems, Fock states are often used to describe the number of photons in a given mode of an electromagnetic field. For example, a single-photon Fock state $\|1\rangle$ represents a state with exactly one photon in the mode. These states can be used to encode information for applications such as quantum communication and cryptography.
>
>In mechanical systems, Fock states can be used to describe the vibrational modes of mechanical resonators such as nanomechanical oscillators or superconducting resonators. These systems can be used for applications such as sensing and signal processing.

Real-time feedback correction, which is a method that adjusts the system based on the error information, goes beyond the minimum requirements for a successful QEC in a photonic qubit placed in a **microwave cavity** (a container that can hold electromagnetic waves). This ensures that code words (sequences of qubits that encode information) stay distinguishable from each other. The error-detection process used in this approach allows QEC codes to handle the loss of more than one photon. This process includes encoding quantum information, measuring **error syndrome** (identifying what errors have occurred), correcting errors in real-time, and decoding the information.

The experiments in this study use a combination of a superconducting transmon qubit and a microwave cavity to control multiple photon states for QEC effectively. The error syndrome measurement is done through a projection measurement scheme, which uses a classical microwave pulse. This method has potential benefits for adapting to different error types and being sensitive to small errors in the qubits.

The QEC process can be implemented for the **binomial code** (a specific encoding scheme), but some practical imperfections limit its performance. The QEC method with binomially encoded logical qubits can protect against **single-photon-jump errors** (errors caused by the loss of one photon) through continuous error detection and correction.

> **Binomial code**
>
>Binomial code is used to protect quantum information stored in bosonic systems, such as microwave cavities or optical fibers. In the binomial code, the logical qubit is encoded in photon-number states of a cavity, and the error syndrome is determined by the parity of the photon number.
>
>Specifically, when a single-photon-loss error occurs, the quantum information is projected into an error space spanned by two states: $\|0\rangle$ and $\|1\rangle$. These states correspond to even and odd photon numbers, respectively. The parity of the photon number acts as the error syndrome to distinguish these two spaces.
>
>The binomial code is a stabilizer code, which means that it can detect and correct errors without measuring the state of the logical qubit directly. Instead, measurements are made on ancillary qubits that are entangled with the logical qubit. These measurements allow for real-time correction operations to be applied to recover quantum information stored in the cavity.

These imperfections include a probability of losing two photons during idle time, interference between single-photon-loss errors and **self-Kerr interaction** (a nonlinear optical effect), and imperfect recovery operations at the quantum level. To mitigate these imperfections, some strategies include choosing an optimal waiting time, using a two-layer QEC process (a more advanced error correction method), and adopting the photon-number-resolved a.c. Stark shift (PASS) method during idle operations.

> **Self-Kerr interaction**
>
>The Self-Kerr interaction is a type of nonlinear optical effect that occurs when light interacts with a material medium. In this interaction, the intensity of the light changes the refractive index of the medium, which in turn affects the propagation of the light. Specifically, as the intensity of the light increases, so does the refractive index of the medium. This causes a self-focusing effect, where light waves are focused to a smaller spot size than they would be in a linear medium.

> **Stark shift method**
>
>It is the method to mitigate the effects of photon loss-induced dephasing in logical qubits. This technique is named after the Stark effect, which is a phenomenon in atomic physics where an external electric field causes a shift in the energy levels of an atom.
>
>In the PASS method, an off-resonant drive pulse with a frequency detuning is applied to an auxiliary qubit during the idle operation. This results in different phase accumulation rates for Fock states with different photon numbers relative to the vacuum state. By choosing an optimal amplitude of the detuned drive, it is possible to achieve an error-transparent condition that mitigates the dephasing effect of the logical qubit.

The effectiveness of a QEC procedure is measured by the process fidelity, which compares the actual outcome with the ideal outcome. Without a QEC operation, the inability to protect quantum information from single-photon-loss errors reduces the process fidelity to 0.73. However, using one-layer and two-layer QECs can improve this value. The measured process fidelities for the corrected binomial code with one-layer and two-layer QECs show a slow decay, indicating an improvement over the minimum requirements for a successful QEC by factors of 1.2 and 2.9, respectively.

This study demonstrates a way to increase the coherence time of quantum information encoded with discrete variables by using repetitive QEC. The main source of inaccuracy comes from the two-photon-loss error, which can be corrected by higher-order binomial codes. This research provides practical guidance for optimizing quantum control systems and designing QEC procedures for future applications of logical qubits, making it more accessible for physics undergraduate students.

>**Required Additional Study Materials**
>
> - “Quantum Error Correction” by Daniel A. Lidar and Todd A
> - Joschka Roffe (2019) Quantum error correction: an introductory guide, Contemporary Physics, 60:3, 226-245, DOI: 10.1080/00107514.2019.1667078

**<U>Reference</U>**

Ni, Z., Li, S., Deng, X. et al. Beating the break-even point with a discrete-variable-encoded logical qubit. [Nature 616, 56–60 (2023). ](https://doi.org/10.1038/s41586-023-05784-4)

-----

