---
title: "Brief Reviews of Science: Volume 380, Issue 6642 (April 21, 2023)"
excerpt: "Brief Review on 'Schrödinger cat states of a 16-microgram mechanical oscillator' and 'Scaling information pathways in optical fibers by topological confinement' "

header:
  overlay_image: /assets/images/Science_Journal.png
  overlay_filter: rgba(4, 56, 115, 0.7)

categories:
  - Brief Review
tags:
  - [Quantum Mechanics, Optical Fibers]

toc: true
toc_sticky: true
 
date: 2023-04-27
last_modified_at: 2023-04-27
---

This review is written by **non-expert** and used for **personal** study only.
{: .notice--danger}

## Schrödinger cat states of a 16-microgram mechanical oscillator
- **<U>Quantum Mechanics</U>**

State superpositions, a **fundamental concept in quantum mechanics**, have never been directly observed in the macroscopic world. This has led to numerous explanations, including the inherent complexity of macroscopic objects and the influence of decoherence. Investigating state superpositions in larger objects is essential for **testing the validity of quantum mechanics** and its potential applications in fields such as **parameter estimation and quantum information processing**. Schrödinger's cat, a well-known thought experiment, serves as a vivid illustration of quantum state superpositions.

Numerous experiments have been conducted to demonstrate Schrödinger cat states, which are superpositions of two or more states with distinct phase-space distributions. These experiments have utilized various systems, including trapped ions, electromagnetic waves, superconducting devices, and atomic clouds. In this particular study, the researchers successfully demonstrated the preparation of cat states in the motional degree of freedom of a **solid-state mechanical resonator**.

The experimental apparatus involves a device called an ℏBAR, which consists of a high-overtone bulk acoustic-wave resonator connected to a superconducting transmon qubit. The qubit allows for the generation, manipulation, and measurement of phonon states within the resonator. The entire device is housed in a three-dimensional Al cavity, enabling control via standard circuit quantum electrodynamics (cQED) techniques. The acoustic free spectral range is approximately 12 MHz, and the qubit's frequency can be tuned to address various longitudinal phononic modes.

To create a cat state, the researchers employed the **Jaynes-Cummings interaction**, which occurs between the qubit and phonon when they are in resonance. The phonon mode is prepared in a coherent state with a sufficiently large amplitude, while the qubit is set to either the ground or excited state. The interaction between the qubit and phonon results in Rabi oscillations and a subsequent collapse of the oscillations' amplitude, ultimately leading to entangled qubit and phonon states. At a specific point in time, the state becomes separable, creating a cat state in the phonon mode. This cat state arises from the time evolution of the reduced phonon state in phase space, causing the coherent states to rotate and distort. At the revival time, the two phonon state components nearly recombine in phase space.

The researchers experimentally verified the **predicted collapse and revival of Rabi oscillations** and the creation of mechanical cat states in the phonon mode. They displaced the phonon mode to a coherent state using a resonant drive and prepared the qubit in its initial state by cooling it with an auxiliary phonon mode. They then measured the qubit's excited state population and observed oscillations that collapsed and later revived, indicating the coherent exchange of energy quanta between the qubit and phonon mode. By conducting full Wigner tomography of the phonon state after the resonant interaction times, they measured the Wigner functions, which displayed the distribution of populations in the phonon Fock states for coherent states created with varying drive amplitudes.

Using the ℏBAR device, the researchers confirmed the creation of mechanical cat states in the phonon mode. They employed the Jaynes-Cummings interaction between the qubit and phonon on resonance to generate the cat state, observing the collapse and revival of Rabi oscillations as well as the creation of the cat state in their experimental results. Full Wigner tomography of the phonon state after the resonant interaction was used to measure the phonon subsystem's evolution, with the data confirming the transformation of the initial coherent state into a cat state at a particular time. They estimated the cat state's size using maximum-likelihood reconstruction of the phonon state, which yielded a **fidelity of 76% to an analytical state** with an initial coherent state size of 1.62. The researchers also simulated the full experimental protocol with independently measured system parameters, showing good agreement with the measurements.

The state obtained in the experiment resembles a type of cat state known as **two-component coherent state superpositions (CSS)**, which are often used in quantum information and parameter estimation protocols. The state can be fit to an analytical expression of the CSS state, and the size of the state can be measured as half the phase space distance between the coherent state components. This size corresponds to a maximal delocalization of 7.0 times the zero point motion of an equivalent 1D quantum harmonic oscillator, which translates to an effective mass of approximately 16.2 milligrams, delocalized over a distance of $2.1 × 10^{-18}$ meters. The fidelity of the reconstructed state to the CSS state is about 66%.

The researchers demonstrated the creation of mechanical cat states in the phonon mode using the **Jaynes-Cummings interaction** with the qubit and phonon on resonance. They experimentally confirmed the collapse and revival of Rabi oscillations and the creation of mechanical cat states. The size of the cat state can be controlled by varying the amplitude of the phonon displacement drive. The researchers also demonstrated the preparation of six cardinal points of the Bloch sphere by initializing the transmon qubit state in all six cardinal points. The phonon subspace maps onto that of the cat state encoding in the limit of large cat state size.

The study investigated the **quantum-to-classical transition** of different-sized cat states by letting them evolve freely for a varying wait time before performing Wigner tomography. The non-classicality of the state was measured using time-dependent negativity. The results show that the negative features disappear on a time scale much faster than $T_{ph}^1$, the energy relaxation time of the phonon mode. The extracted decay time scales, $\tau_{cat}$, were plotted, which show faster-decaying negativity for larger-sized cat states. For small values of $a$, $\tau_{cat}$ deviates from this expression and depends on the exact state's properties, such as the superposition's phase.

The study demonstrates the generation of cat states in a microgram-mass solid-state mechanical mode using **cQED** tools. The results pave the way for tests of wave function collapse models and quantum-enhanced sensing. The maximum size of the cat state that can be prepared is currently limited by device parameters, including qubit and phonon decoherence rates. The study highlights the importance of phase-space separation of state components for **error protection of encoded qubits** and the presence of interference fringes with high Fisher information for **quantum-enhanced sensing**. The study suggests that improvements in qubit and phonon resonator properties can enable alternative cat state generation protocols that can lead to states with a higher fidelity to a CSS state.



>**Required Additional Study Materials**
> 
> - A. Bassi, K. Lochan, S. Satin, T. P. Singh, H. Ulbricht, Models of wave-function collapse, underlying theories, and experimental tests. Rev. Mod. Phys. 85, 471–527 (2013).
> <details>
> <summary>Introductory material</summary>
> <div markdown="1">
> - **“Principles of Quantum Mechanics”** by R. Shankar
> </div>
> </details>

**<U>Reference</U>**

SCIENCE 20 Apr 2023 Vol 380, Issue 6642 pp. 274-278 DOI: 10.1126/science.adf755

<br>

## Scaling information pathways in optical fibers by topological confinement
- **<U>Optical Fibers</U>**

The paper explores the **potential of topologically** confined modes (TCMs) in optical fibers to enhance information capacity and minimize energy consumption in classical communication networks, as well as to advance the development of quantum computing networks. Current approaches to exploiting space in optical fibers include multimode fibers (MMFs) and multicore fibers (MCFs), both of which have their limitations. MMFs offer high spatial efficiency but are prone to mode mixing, while MCFs provide deployment simplicity but suffer from limited channel count due to cross-talk. TCMs, however, enable the transmission of light over long distances with a record number of low-loss spatial modes and negligible mode coupling, even when the fiber is tightly bent. This method combines the advantages of MMFs and MCFs and can be implemented across multiple spectral bands used in telecommunications.

**Topological confinement**, a concept introduced in the paper, is a mechanism that confines a photon to a fiber due to a centrifugal barrier created by the light's orbital angular momentum (OAM). The authors employ a heuristic ray picture to illustrate this idea and reveal that the confinement loss of unbound, radiative modes diminishes as the mode's azimuthal index increases. A more comprehensive understanding of topological confinement is obtained by examining the waveguide eigenvalue equation, which incorporates the refractive index profile of the fiber, the free-space wave vector of light, and the propagation constant of an eigenmode. The modified effective potential enabling topological confinement is defined as $n^2(r) - \frac{L^2}{k_0^2 r^2}$.

The paper presents a graph of the topologically modified profile, ncentrifugal(r), for cutoff modes with three nonzero azimuthal indices, $L$, calculated at various wavelengths to achieve identical effective indices. The graph indicates that as the azimuthal index increases, cutoff modes encounter refractive index barriers of progressively greater magnitudes. Additionally, the authors present a simulated confinement loss versus azimuthal index for modes with different radial orders in a step-index fiber. The graph demonstrates that modes with low azimuthal indices and high radial orders are highly lossy, but for first radial order modes with sufficiently high azimuthal indices, confinement loss decreases significantly, reaching as low as ~$10^{-6}$ dB/km. This behavior of topologically confined modes with high azimuthal indices suggests that they mirror the behavior of conventional total internal reflection (TIR) bound modes, despite not satisfying TIR conditions.

The paper also presents a graph of simulated confinement loss versus relative topological charge for five different step-index fibers with identical index contrasts and core diameters ranging from 15 to 75 mm. The graph reveals that the number of modes with confinement loss significantly lower than that of conventional transmission fibers increases with the difference between the topological charge of the cutoff mode and the topological charge of the last bound mode guided by conventional TIR before cutoff. This implies that TCMs can be found in any highly multimoded waveguide with a discrete index step at its outer core boundary. The authors then present experimental cutback loss measurements on SOa and SOaa modes with a radial order of 1 and azimuthal indices ranging from 25 to 43 in a ring-core fiber. The measured loss for TCMs is orders of magnitude lower than conventional wisdom suggests for cutoff modes, supporting the idea that centrifugal barriers significantly assist light transmission for modes expected to be radiated away. The paper proposes that further glass viscosity and drawing parameter optimizations hold the potential to considerably reduce losses for TCMs, and manufacturing optimizations are anticipated to substantially decrease TCM losses to levels similar to those of commercial high-index-contrast single-mode fibers.

The paper highlights that topological confinement of light in multimode fibers offers a major advantage of natural immunity to mode mixing. Highly multimoded fibers are susceptible to mode mixing due to the different dispersion relationships of their modes, which result in degeneracies. However, topologically confined modes (TCMs) exhibit markedly distinct behavior. Although some TCMs display degeneracies with high-m modes, they maintain clean measured modal output images because of the orders-of-magnitude difference in confinement losses, leading to frustration of phase-matched coupling. This enables the scaling of mode count while reducing the modal density of states responsible for unwanted perturbative mixing.

The researchers characterized a multimode fiber featuring **topological charge modes (TCMs)** guided by centrifugal barriers, as opposed to total internal reflection (TIR) found in conventional fibers. Their findings indicate that TCMs experience much lower cross-talk and are less susceptible to mode mixing compared to TIR-bound modes. These characteristics make TCMs suitable for high-dimensional encoding and quantum transport. The researchers demonstrated a **kilometer-length fiber with a record-high mode count** (approximately 50) and low cross-talk, and they suggest that manufacturing optimizations could reduce the current losses (approximately 5.0 dB/km for TCMs and 1.4 dB/km for TIR-bound modes) to levels appropriate for longer telecommunications links.

The paper details the discovery and demonstration of **topologically confined modes (TCMs) in multimode fibers**, which exhibit improved mode-coupling resistance compared to traditional multimode fibers. TCMs display low cross-talk, high channel counts, large mode areas, and extreme bend tolerance, making them a promising platform for classical and quantum telecommunications, fiber lasers, and nonlinear signal processing. Manufacturing optimizations are expected to further reduce TCM losses, making them suitable for longer telecommunications links. Additionally, the authors discuss the potential for TCMs to enable high-dimensional encoding and intermodal interaction for quantum transport.

>**Required Additional Study Materials**
> 
> - M. Erhard, M. Krenn, A. Zeilinger, Advances in high-dimensional quantum entanglement. Nat. Rev. Phys. 2, 365–381 (2020).
> - “Multicore and multimode optical amplifiers for space division multiplexing” in Optical Fiber Telecommunications VII, A. E. Willner, Ed. (Academic Press, 2020)
> <details>
> <summary>Introductory material</summary>
> <div markdown="1">
> - **“Understanding Fiber Optics”** by Jeff Hecht
> - **“Fiber-Optic Communication Systems”** by Govind P. Agrawal
> </div>
> </details>

**<U>Reference</U>**

SCIENCE 20 Apr 2023 Vol 380, Issue 6642 pp. 278-282 DOI: 10.1126/science.add1874