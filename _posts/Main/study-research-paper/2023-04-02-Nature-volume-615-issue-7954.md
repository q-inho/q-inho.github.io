---
title: "[Brief Review] Nature, Volume 615 Issue 7954, 30 March 2023"
excerpt: "Brief Review on 'Determining the gluonic gravitational form factors of the proton' and 'Universal logic with encoded spin qubits in silicon"


categories:
  - Study/Research/Paper
tags:
  - [Particle Physics, Quantum Computing]

toc: true
toc_sticky: true
 
date: 2023-04-02
last_modified_at: 2023-04-03
---

This review is written by **non-expert** and used for **personal** study only.
{: .notice--danger}

# Determining the gluonic gravitational form factors of the proton
- **<U>Experimental Particle Physics</U>**

The study focuses on understanding the **gluonic gravitational** form factors of the proton. To understand what this means, it's helpful to first understand some background information about particle physics.

The proton is a subatomic particle that is composed of smaller particles called quarks and gluons. Quarks are held together by gluons, which are the carriers of the strong nuclear force that binds protons and neutrons together in atomic nuclei.

<p align="center">
  <img src="https://user-images.githubusercontent.com/79438062/229382391-7b4b48cd-0cac-4974-b30b-a71e0ea2956f.png" alt="Source: Wikipedia">
<br> <b>Gluon, g</b>. In Feynman diagrams, emitted gluons are represented as helices. This diagram depicts the annihilation of an electron and positron. Source: Wikipedia
</p>


In addition to the strong nuclear force, there are three other fundamental forces in nature: electromagnetism, weak nuclear force, and gravity. Electromagnetism is responsible for interactions between charged particles, while weak nuclear force is responsible for certain types of radioactive decay. Gravity is responsible for the attraction between massive objects.

In particle physics, form factors are mathematical functions that describe how a particle interacts with other particles or fields. In the case of the proton, form factors can be used to describe how it interacts with electromagnetic fields (such as those produced by a photon) or gravitational fields (such as those produced by other massive objects).

The researchers in this study were specifically interested in determining the gluonic gravitational form factors of the proton. This refers to how gluons contribute to the gravitational mass of the proton. Gravitational mass is a measure of how much an object responds to a gravitational field - in other words, how much gravity it produces and how much gravity it feels from other objects.
To investigate this phenomenon, the researchers used a small color dipole and threshold photoproduction of the J/ψ particle. A color dipole refers to two quarks that are separated by a distance - this creates an electric dipole moment that can interact with electromagnetic fields. The J/ψ particle is a type of meson that contains one charm quark and one charm anti-quark.

By using these tools, the researchers were able to investigate the gravitational density of gluons. They then analyzed their data using various models and were able to determine the gluonic gravitational form factors of the proton from their measurements.

One interesting finding from this study is that they determined a **mass radius** that is notably smaller than the electric charge radius. This means that there is more mass concentrated in a smaller volume than would be expected based on just looking at the electric charge distribution of the proton.

The researchers used a variety of models to analyze their data, including vector meson dominance (VMD), generalized vector dominance (GVD), and holographic QCD. VMD is a model that describes the interaction between photons and hadrons (particles made up of quarks and gluons). GVD is a more general version of VMD that includes additional mesons. Holographic QCD is a theoretical framework that uses string theory to describe the strong nuclear force.

In all cases, the researchers found that their determined mass radius was smaller than the electric charge radius. This suggests that there is more mass concentrated in a smaller volume than would be expected based on just looking at the electric charge distribution of the proton.

In some cases, depending on the model used, they found that their determined radius agrees well with first-principle predictions from lattice quantum chromodynamics (QCD). Lattice QCD is a computational technique used to study the strong nuclear force. It involves discretizing space-time into a lattice and using numerical simulations to calculate properties of particles such as quarks and gluons.

Overall, this research helps us better understand how gluons contribute to the gravitational mass of visible matter. It also has potential applications in fields such as nuclear physics and astrophysics, where understanding these properties can help us better model and predict phenomena such as neutron stars and black holes.

One interesting aspect of this study is that it highlights some of the challenges involved in studying subatomic particles. For example, because quarks are always confined within hadrons like protons, it can be difficult to directly measure their properties. Instead, researchers often have to rely on indirect methods like those used in this study.

Another challenge is that subatomic particles are subject to quantum mechanics, which means that their properties can be described by probability distributions rather than exact values. This can make it difficult to draw definitive conclusions from experimental data.

>**Required Additional Study Materials**
>
> - [Particle Physics and Universe](https://q-inho.github.io/general/Study-Roadmap-for-Physics/#particle-physics-and-the-universe)
> - “An Introduction to Quantum Field Theory” by Michael E. Peskin and Daniel V. Schroeder
> - “Quantum Chromodynamics” by Walter Greiner and Stefan Schramm
> - “Gauge Theories in Particle Physics: A Practical Introduction” by Ian J.R. Aitchison and Anthony J.G. Hey 

**<U>Reference</U>**

Duran, B., Meziani, ZE., Joosten, S. et al. Determining the gluonic gravitational form factors of the proton. [Nature 615, 813–816 (2023).](https://doi.org/10.1038/s41586-023-05730-4)

# Determining the gluonic gravitational form factors of the proton
- **<U>Quantum Information</U>**

Fault tolerance is crucial for useful quantum hardware, requiring well-isolated qubits controlled with precision and high speed. Lithographically defined qubits, such as superconducting transmons or single electron spins in Si quantum dots, have made significant progress in scaling and control fidelity. However, achieving fault tolerance also depends on the structure and correlation of errors, which can be mitigated by using degenerate qubit states and coherent partial swap interactions. This alternative approach to quantum computation evokes classical conservative logic and allows for traversing the very large continuous special unitary group of $SU(2^n)$ for large n.

The researchers use a subsystem that encodes n/3 qubit states in n spins, with the remaining spins called leakage states. This allows for multi-qubit encoded universal quantum logic and avoids correlated errors. The partial swap operation needed for decoherence-free subspace (DFS) qubits is implemented using the contact exchange interaction between lithographically defined quantum dots, with a critical design difference being the removal of variation in spin splittings to maintain encoded-state degeneracy.

> **DFS qubit**
>
> These are a type of qubit that is designed to be less susceptible to decoherence, which is the loss of quantum information due to interactions with the environment. Decoherence is a major challenge in quantum computation, as it can cause errors and limit the performance of qubits. DFS qubits are designed to be more robust against certain types of environmental noise and can potentially enable more reliable quantum computation.

The device confines electrons in a silicon well with isotopic enhancement to reduce magnetic field gradients and control errors, and uses metallic gates to control interactions between electrons in quantum dots.

The SLEDGE platform allows for improved yield in the fabrication of quantum dots for practical EO operation in extended arrays. The SLEDGE architecture readily allows for extension of this geometry to 2d arrays by stacking via-connected routing layers, enabling 2d codes using high-fidelity native encoded-SWAP operation.

> **EO operation**
>
> EO operation refers to the energy-degenerate encoded qubit states controlled by nearest-neighbour contact interactions that partially swap the spin states of electrons with those of their neighbors, which is the alternative approach to quantum computation presented in the paper. The authors demonstrate this approach using silicon-based spin qubits and show that it is possible to perform universal logic operations with high fidelity. EO operation is different from traditional methods that rely on injecting microwave energy matching qubit resonances, which can lead to correlated errors and make achieving fault tolerance challenging.

Qubits are encoded using spins capable of partial swaps by associating quantum information with the total angular momentum quantum number of pairs of two spins. Addition of a third unmeasured spin to each qubit enables individual qubit control with only exchange, and no additional physical mechanism is needed to generate entanglement between these encoded qubits. Qubit preparation and measurement is achieved with Pauli spin blockade, which maps spin parity to the more easily detected charge configuration.

The researchers used baseband voltage pulses to control their encoded qubits through nearest-neighbor interactions. They achieved this by temporarily raising the exchange energy $J_{Xn}$ to $J_{Xn}/h \approx 100$ MHz using a single exchange pulse.

The researchers used FW-CNOT and SWAP gates for quantum computing and characterized their performance using quantum process tomography (QPT) and randomized benchmarking (RB). QPT showed qualitative agreement with expected results, but was limited by SPAM errors. RB was preferred as it was fast, simple, and relatively insensitive to SPAM error. The average two-qubit Clifford fidelity was 97.1% ± 0.2%, which was better than suggested by QPT and comparable to contemporary single silicon spin qubit two-qubit RB errors.

> **FW-CNOT gate**
>
> FW-CNOT is a type of controlled-NOT (CNOT) gate that is used in quantum computation. The "FW" in FW-CNOT stands for "flip-flop and wait", which refers to the way the gate operates. The FW-CNOT gate is designed to flip the state of a target qubit if and only if the control qubit is in a specific state. This gate can be used as a building block for more complex quantum circuits and algorithms.

> **Quantum Process Tomography**
>
> Quantum process tomography (QPT) is a technique used to characterize the behavior of a quantum system. It involves applying a known set of input states to the system and measuring the corresponding output states. By analyzing the input-output relationship, it is possible to reconstruct the quantum process that describes how the system evolves over time. QPT can be used to identify errors and imperfections in a quantum system, which can help improve its performance and reliability.

> **Randomized Benchmarking**
>
> Randomized benchmarking (RB) is a method used to characterize the performance of quantum gates. It involves applying a randomly selected sequence of gates that compile to the identity from a discrete group of qubit operations, typically the Clifford group, to a quantum system. This choice depolarizes noise in the encoded subspace, allowing gate performance to be inferred by sweeping the sequence length and fitting return probability to an exponential decay. RB is fast, simple, relatively insensitive to SPAM error and requires measurement of only one qubit.

> **SPAM error**
>
> SPAM error refers to errors in state preparation and measurement (SPAM) that can occur in a quantum system. These errors can arise from imperfections in the hardware used to prepare and measure qubits, as well as from environmental noise and other sources of interference. SPAM errors can lead to incorrect measurements of the state of a qubit, which can in turn affect the performance of quantum gates and algorithms.

The performance of individual gates is measured using interleaved randomized benchmarking (iRB). iRB is performed for FW-CNOT and encoded SWAP, finding a fidelity of 96.3% ± 0.7% and 99.3% ± 0.5%, respectively. The SWAP error is more than five times lower than that of CNOT, making it a high-fidelity mechanism for moving data in constrained geometries. The dominant error in the EO operation is due to residual hyperfine interactions from the 800 ppm of 29Si nuclear spins and natural abundance of barrier 73Ge spins.

> **Interleaved Randomized Benchmarking**
>
> Interleaved randomized benchmarking (iRB) is a protocol used to measure the performance of individual gates in a quantum system. In iRB, the operation of interest is repeatedly interleaved between a random Clifford gate, and the resulting decay is compared with a reference RB decay to infer the operation's fidelity. By comparing the decay rates of different gates, it is possible to identify which gates are performing well and which ones need improvement.

Researchers have successfully demonstrated encoded universal quantum logic operations using exchange-based partial swap interaction, which offers near-term opportunities for analogue simulation and potential for other computational modalities. Achieving fault tolerance with this method would require improved gate fidelity through faster control or improved isotopic purification.

**<U>Reference</U>**

Weinstein, A.J., Reed, M.D., Jones, A.M. et al. Universal logic with encoded spin qubits in silicon. [Nature 615, 817–822 (2023).](https://doi.org/10.1038/s41586-023-05777-3)