---
title: "Brief Reviews of Nature Electronics: Volume 5, Issue 1 (January, 2022)"
excerpt: "Brief Review on 'A cryo-CMOS chip that integrates silicon quantum dots and multiplexed dispersive readout electronics' "

header:
  overlay_image: /assets/images/Nature_Electronics_Journal.png
  overlay_filter: rgba(2, 115, 94, 0.7)

categories:
  - Brief Review
tags:
  - [Quantum Information]

toc: true
toc_sticky: false
 
date: 2023-04-20
last_modified_at: 2023-04-20
---

This review is written by **non-expert** and used for **personal** study only.
{: .notice--danger}

## A cryo-CMOS chip that integrates silicon quantum dots and multiplexed dispersive readout electronics
- **<U>Quantum Information</U>**

### Introduction to Quantum Computing and Silicon Quantum Dots

This article explores the potential of quantum computing to solve complex problems more efficiently than classical computing. However, building the necessary quantum hardware remains a significant challenge. One promising solution involves using single electron spins trapped in silicon quantum dots (QDs), which are tiny semiconductor structures that can host quantum bits or "qubits." Recent advancements have demonstrated long coherence times, high-fidelity spin readout, and one- and two-qubit gates, fulfilling the basic requirements for building a quantum computer approaching fault-tolerant thresholds.

### Large-Scale Quantum Computer Designs and Integration Challenges

Different designs for large-scale quantum computers in silicon have been developed, all sharing a common concept: using metal-oxide-semiconductor (MOS)-based QD arrays to host qubits and digital and analog classical electronics for control and readout. A fully integrated system would lead to a reduced size, easier signal synchronization, decreased latency, and minimized inter-chip wiring. However, integrating classical electronics with quantum devices at extremely low temperatures is challenging due to the limited cooling power available for typical classical electronics. Investigating the limits of integration is crucial for creating a complete solid-state quantum processor.

### New Approach for Efficient and Scalable Readout of Silicon QDs

The article introduces a new approach for efficiently and scalably reading out a non-interacting array of silicon quantum dots (QDs) operating at extremely low (millikelvin) temperatures. This is achieved using an industrial 40 nm complementary metal–oxide–semiconductor (CMOS) technology. The readout process uses gate-based microwave reflectometry, which is fully integrated on the chip. By combining time- and frequency-domain multiplexing, the number of readout resonators per QD can be scaled sublinearly while maintaining a degree of parallel readout suitable for quantum error correction. This circuit can be expanded by replicating its basic building blocks to create a large-scale readout platform. This approach provides a potential solution to the challenge of integrating classical electronics with quantum devices and may enable the construction of a full-fledged solid-state quantum processor.

### Quantum-Classical Readout Interface Architecture, Implementation, and Future Prospects
The article presents a new architecture for a quantum-classical readout interface that is fully integrated using an industrial 40 nm bulk CMOS technology. This architecture consists of a 3 x 3 array of nine identical cells, each containing a silicon QD device implemented as a MOS transistor. The cells are arranged in a row-column random-access configuration, similar to a dynamic random-access memory (DRAM). Each cell is connected to a shared data-line signal and an LC resonator to perform microwave reflectometry readout. This architecture significantly reduces the resources needed for the control and readout of N quantum devices from N to just 2N lines and N resonators, greatly simplifying the circuit complexity of current paradigms. This architecture could potentially enable the construction of a large-scale readout platform for quantum computers.

### Minimum-Size nMOS Transistors as QD Devices
The article explains the design and implementation of minimum-size nMOS transistors as QD devices in an industrial CMOS technology. When these devices are cooled down to 50 mK and a positive voltage is applied, single electrons are trapped in the small area under the gate at the oxide-silicon interface, forming few-electron QDs. Coulomb diamonds are observed in the source-drain current as a function of the voltage for the QD transistor $Q_{33}$. From this plot, a charging energy is extracted, which enables electron trapping even at 4.2 K. All nine devices in the matrix exhibit Coulomb-blockade oscillations at 50 mK. 

### Access Transistor-QD Cell Functionality and Readout

The article demonstrates the functionality of the access transistor-QD cell and highlights the allowed and forbidden regions for readout . When the access-transistor channel resistance becomes comparable to the QD-transistor gate leakage resistance, the effective equilibrium gate voltage for the QD transistor is reduced, and the QD can be decoupled from the data line. However, when the voltage is above a certain threshold, Coulomb-blockade oscillations are observed as a function of the voltage. This demonstrates the realization of a quantum-classical integrated circuit (IC) in industrial bulk CMOS technology at 50 mK.

### Microwave Frequency Characterization of Resonators

The article describes the microwave frequency characterization of the resonators, which are designed to have different resonant frequencies to enable frequency-selective readout over the corresponding rows. The frequency spectrum for the integrated LC resonators with three minima at resonant frequencies of $f_1$ = 6.810 GHz, $f_2$ = 7.374 GHz, and $f_3$ = 7.941 GHz observed at 300 K. The resonators were designed to match the high impedance of the gate of the QD device to the 50 Ω microwave input when the access transistors are on, allowing maximum power transfer and enhanced sensitivity.

### Resonators as Sensors for Integrated Gate-Based Dispersive Readout

Operating at a higher readout frequency has several advantages, including reducing the footprint of the inductors, higher Q factors critical for the sensitivity of the technique, and higher sensitivity of gate-based dispersive readout resonators. The achieved Q factors are modest but represent the state-of-the-art of what can be accomplished with industrial CMOS.

The article describes the use of resonators as sensors to perform integrated gate-based dispersive readout of the QD charge states. The resonators produce an oscillatory voltage on the gate of the QDs, resulting in the cyclic tunneling of electrons to and from the electronic reservoirs. The method is benchmarked by performing DC transport measurements for device $Q_{13}$, and the results are compared with those measured via reflectometry. Gate-based sensing is efficient in detecting electronic transitions even if the QDs are offset from the center of the channel and present low tunnel rates to one ohmic contact. The data analysis reveals a signal-to-noise ratio of 28.7 in 400 ms of integration time and a tunnel rate to the source of 48.3 GHz for peak α, representing the demonstration of fully integrated conditional gate-based readout of QDs implemented in an industrial CMOS technology.
Section 9: Time- and Frequency-Multiplexed Readout Demonstrations
The authors perform time-multiplexed reflectometry measurements of QD devices in the same row by addressing them at the frequency of the shared resonator and activating the corresponding columns one after the other. They use Resonator1 with a carrier frequency fmw1 = 6.872 GHz and use the 1 x 3 QD array [Q1j]. The authors measure the charge stability diagrams for each individual Q1j and use such data as the control set. They then perform the dynamic characterization in the time-domain multiplexing and compare the results. The authors show that the match between the control set and dynamic measurements indicates the success of the protocol. Time-domain multiplexing can be performed in a random-access manner similar to DRAM architectures, which represents fully integrated time-multiplexed reflectometry measurements of silicon QDs and demonstrates an important reduction in the analog infrastructure required for the readout of quantum circuits, as multiple devices can be read by a single resonator.
The authors demonstrate the frequency-multiplexed readout of two independent QDs on different rows of the matrix using Resonator2 at $f_{mw2}$ = 7.419 GHz and Resonator1 at $f_{mw1}$ = 6.873 GHz. They activate column 2 and ramp up VDL1 and VDL2 to activate rows 1 and 2, respectively, obtaining a 2 × 1 parallel set of Coulomb peak transitions from $Q_{12}$ and $Q_{22}$. The authors highlight that parallel readout reduces the overall integration time to read large quantum circuits and is particularly relevant to quantum error correction (QEC) sequences, such as the surface code, which requires continuous qubit readout at scale.

### Integrated Time- and Frequency-Multiplexed Gate-Based Readout

The authors demonstrate the integration of time- and frequency-multiplexed gate-based readout for silicon quantum dots on a single chip. They use resonators as sensors to perform gate-based dispersive readout of the quantum dot charge states. They perform time-multiplexed reflectometry measurements of QD devices in the same row by addressing them at the frequency of the shared resonator and activating the corresponding columns, one after the other. They also demonstrate frequency multiplexing by addressing rows with different frequencies using two independent resonators. Finally, they combine time- and frequency-domain multiplexing for readout of multiple QDs in a fully integrated platform with a scalable architecture.

### Conclusion and Future Directions

The study demonstrates the integration of silicon quantum dots, digital addressing, and multiplexed analog readout electronics in a cryogenic integrated circuit fabricated using industrial 40 nm CMOS technology. The results provide a scalable, integrated platform for silicon-based quantum processors. Single-qubit control is possible in the few-electron regime, and two-qubit gates may be achieved by bringing the cells in close proximity, which would require a shorter gate pitch or smaller technology node.
The authors note that their work demonstrates the full integration of quantum devices and classical electronics on a single chip operating at millikelvin temperatures with a limited power budget. They suggest that their architecture could be improved in the future to allow for two-qubit gates, and to improve readout signal-to-noise ratio and speed by using industry-compatible superconductors and amplification methods. They also suggest that their approach could be combined with other readout and control methods at higher temperatures to enable larger circuit complexity.





>**Required Additional Study Materials**
>
> - Montanaro, A. Quantum algorithms: an overview. npj Quantum Inf. 2, 15023 (2016).
> - Vandersypen, L. M. K. et al. Interfacing spin qubits in quantum dots and donors—hot, dense, and coherent. npj Quantum Inf. 3, 34 (2017).
> - Reilly, D. J. Engineering the quantum-classical interface of solid-state qubits. npj Quantum Inf. 1, 15011 (2015).

**<U>Reference</U>**

Ruffino, A., Yang, TY., Michniewicz, J. et al. A cryo-CMOS chip that integrates silicon quantum dots and multiplexed dispersive readout electronics. [Nat Electron 5, 53–59 (2022). ](https://doi.org/10.1038/s41928-021-00687-6)

<br>