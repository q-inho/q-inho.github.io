---
title: "Brief Reviews of Science Advances: Volume 8, Issue 49 (December 9, 2022)"
excerpt: "Brief Review on 'EAdaptive optimal control of entangled qubits' and 'Diamond-based microwave quantum amplifier "


header:
  overlay_image: /assets/images/Science_Advances_Journal.png
  overlay_filter: rgba(4, 56, 115, 0.7)


categories:
  - Brief Review
tags:
  - [Quantum Information]

toc: true
toc_sticky: true
 
date: 2023-04-09
last_modified_at: 2023-04-09
---

This review is written by **non-expert** and used for **personal** study only.
{: .notice--danger}

# Adaptive optimal control of entangled qubits
- **<U>Quantum Information</U>**

Optimal control theory has found extensive applications in diverse fields such as NMR, quantum error correction, and cold atoms. Numerical techniques for calculating spin system dynamics are vital in these contexts, but computational load can be minimized by ensuring consistent **high precision** throughout the optimization process.

QOALA, an **adaptive optimal control approach**, efficiently solves optimal control problems for entangled qubit systems without compromising accuracy. By utilizing a collection of approximate propagators that offer variable trade-offs between precision and computational cost, QOALA achieves a considerable speedup in practice.

The goal of optimal control is to **identify the ideal control parameters for reaching a desired state or propagator**. To find these optimal parameters, the objective function is maximized. Fidelity functions, which measure the overlap between desired and actual states or propagators, are frequently employed as objective functions in optimal control.

Mixed quantum states' similarity can be measured by fidelity functions, which can be maximized using gradient-based optimization methods. The fidelity function's gradient can be calculated using the chain rule and Fréchet derivatives. An adaptive technique is suggested to select numerical solvers with varying cost and accuracy trade-offs based on closeness to the optimum. This method comprises error estimation for calculated fidelity and a proximity measure to the optimum.

Two distinct spin systems, a two-spin and a three-spin system, both heteronuclear with 2M controls and a pulse B1 amplitude limited to 1 kHz, are investigated for the state transfer problem. The optimal control task for a four-spin system is made more challenging by **initializing the entangled multi-spin state** and **incorporating a relaxation term** in the uncontrolled portion of the Hamiltonian. The convergence of the two-spin system exhibits typical quadratic convergence; however, the second-order splitting solver fails to achieve fidelity above 99% with a time slice width of $δt = 0.2 ms$. Quadratic convergence is also not achieved in the three-spin and four-spin problems.

To optimize spin systems, QOALA alternates between **low-accuracy** and **high-accuracy solvers**, attaining high fidelities while conserving time. For two-spin systems, the convergence trajectory of QOALA closely mirrors the exact method, and significant time savings are observed for four-spin systems. Although universal swap gate problems necessitate longer pulses than state transfer problems, QOALA remains efficient in optimizing them. In a three-spin swap gate, QOALA successfully swaps the first and third spin states while keeping the second spin state constant.

QOALA provides a **balance** between precision and computational expense by initially employing low-cost, low-accuracy approximations and transitioning to high-cost, high-accuracy approximations as it nears the optimum. It predicts an approximate $O(M^2)$ speedup for an $M$ qubit system while preserving optimal solution accuracy. High-order splitting methods are needed for the highest fidelities, with a speedup tendency of $O(M)$ at these high fidelities.

Benchmarking can serve as an alternative approach to error estimation in optimal control problems. Precomputed benchmarking entails determining switch points on a cost versus accuracy graph to minimize overall cost while maximizing accuracy. QOALA is a swift and precise optimal control algorithm for addressing entangled qubit problems without sacrificing accuracy.

>**Required Additional Study Materials**
> 
> - Y.-C. Liang, Y.-H. Yeh, P. E. M. F. Mendonça, R. Y. Teh, M. D. Reid, P. D. Drummond,Quantum fidelity measures for mixed states. Rep. Prog. Phys.82,076001 (2019).
> - J. Munkres, Analysis on Manifolds (CRC Press, 1991).
> - N. J. Higham, Functions of Matrices: Theory and Computation (Society for Industrial and Applied Mathematics, Philadelphia, PA, USA, 2008).
> - J. Nocedal, S. J. Wright, Numerical Optimization (Springer, New York, NY, USA, ed. 2, 2006).
> <details>
> <summary>Introductory material</summary>
> <div markdown="1">
> - “**Quantum Measurement and Control**” by Howard M. Wiseman and Gerard J. Milburn
> </div>
> </details>

**<U>Reference</U>**

Goodwin, D. et al. Adaptive optimal control of entangled qubits. [Science Advances 8 (2022).](https://www.science.org/doi/10.1126/sciadv.abq4244)

-----

# Diamond-based microwave quantum amplifier
- **<U>Quantum Information</U>**

Efficiently amplifying and detecting microwave signals with minimal noise is essential for a range of applications, such as deep-space communications, radio astronomy, and quantum technology. There are three primary types of amplifiers: traditional electronic amplifiers, superconducting circuit-based amplifiers, and solid-state maser devices. Solid-state masers were initially employed in specialized applications, but due to their complex implementation, low operating temperature requirement, and limited bandwidth/gain performance, they have been mostly replaced by conventional electronic amplifiers.

Quantum technology needs the amplification of weak microwave signals while maintaining minimal noise. Although superconducting-based amplifiers are in use, they are limited by extremely low operating temperatures. Maser technology, specifically using nitrogen-vacancy centers in diamond, could offer an alternative approach for achieving low-noise microwave amplifiers that work at higher temperatures, as shown in recent experiments with operational amplifiers.

Researchers have developed an innovative maser quantum amplifier with a minimum gain of 20 dB, a bandwidth of about 10 MHz, and a saturation input power greater than -60 dBm (1 nW). This device achieves low noise performance at temperatures much higher than about 1 K, ideally close to room temperature. A maser starts working when the microwave losses in its cavity, including losses to the environment, are smaller than the net gain produced by the stimulated emission effect. Two distinct methods can be considered for constructing such a device: (i) using a cavity with the highest possible Q factor (a measure of how well the cavity stores energy) and a relatively dilute material, or (ii) using a cavity with a lower Q factor that supports a larger bandwidth and reaches the desired performance through an increase in NV concentration and filling factor.

The experiments studied two modes of the maser device: oscillator and amplifier. To work as an oscillator, the coupling in its two microwave ports was reduced, and it was adjusted to be under-coupled. Maser oscillations were observed at around 100 K and below, with a typical power output ranging from about -110 dBm at 78 K to nearly -75 dBm at 30 K. The experimental estimate for Qm, a critical parameter for determining the maser's performance as an amplifier, is approximately 300, which aligns reasonably well with the expected value of about 212.

The new maser device's two modes of operation, oscillator and amplifier, were discussed in the paper. Measurements were taken for the maser oscillator's output power and oscillation threshold, but its linewidth and phase noise properties were not accurately measured due to magnetic field instability. The maximum available power from the maser oscillator setup can be estimated by optimally simulating the light inside the cavity, considering various factors. To enable practical applications and accurately measure the phase noise of such an oscillator, more stable magnets are necessary, potentially resulting in a unique narrowband microwave source with high short-term stability and very low phase noise.

The researchers evaluated the diamond maser's relevant parameters when operating as an amplifier. The maser's voltage gain-bandwidth product was experimentally determined to be up to 5.8 MHz, which is comparable to the expected theoretical value of 12.2 MHz. However, the calculation method used is not very accurate under the experimental conditions where the maser's Q factor is not significantly smaller than the cavity's Q factor. 

A more precise numerical simulation yields a gain-bandwidth product of about 7.8 MHz, closer to the experimental value. The expected saturation power of the maser as an amplifier was also evaluated using numerical simulation and found to be -55 dBm, aligning with the output obtained in the experiment. The maser's noise temperature was assessed using two different methods, both resulting in a total noise temperature of around 30 K when operating at 30 K. The dominant source of noise in the maser amplifier originated from cavity losses that were not adequately cancelled due to the relatively high Q factor achieved. Ideally, the cavity's Q factor should be significantly smaller than the maser's Q factor. The maser's internal spin noise is quantum-limited, based on the pulsed ESR data that provided the spins' level populations, showing that only the $\|0\rangle$ level is populated.

A solid-state maser amplifier with quantum-limited internal noise has been demonstrated at temperatures above liquid nitrogen. To make the device suitable for modern applications, improvements are needed, particularly in reducing the Qm value. An optimized system would have a Qm of around 50 and a Q0 of approximately 1000, with a practical limit due to high NV concentrations and nearing unity filling factor. The diamond maser device exhibits better noise performance compared to HEMTs for operations at similar frequencies and temperatures but falls short in terms of bandwidth, output power, and system complexity.

Diamond maser technology provides quantum-limited amplification at higher temperatures and increased saturation power compared to superconducting circuits. Traveling-wave masers have superior bandwidth and gain but are more complex. The experimental system demonstrates nonlinear effects, which are crucial for research in the field of cavity quantum electrodynamics.



>**Required Additional Study Materials**
> 
> - X. Gu, A. F. Kockum, A. Miranowicz, Y.-x. Liu, F. Nori,Microwave photonics with superconducting quantum circuits. Phys. Rep.718–719,1–102 (2017).
> - A. E. Siegman, An Introduction to Lasers and Masers (McGraw-Hill Series in the Fundamentals of Electronic Science, McGraw-Hill, 1971)
> - A. Yariv, Quantum Electronics (Wiley, 1967)
> - A. E. Siegman, Microwave Solid-State Masers (McGraw-Hill Electrical and Electronic Engineering Series, McGraw-Hill, 1964)
> - J. F. Barry, J. M. Schloss, E. Bauch, M. J. Turner, C. A. Hart, L. M. Pham, R. L. Walsworth,Sensitivity optimization for NV-diamond magnetometry. Rev. Mod. Phys.92,015004 (2020).
> - C. L. Degen, F. Reinhard, P. Cappellaro,Quantum sensing. Rev. Mod. Phys.89,035002 (2017).
> - F. Jelezko, J. Wrachtrup,Single defect centres in diamond: A review. Phys. Status Solidi A Appl. Mater. Sci.203,3207–3225 (2006).
> <details>
> <summary>Introductory material</summary>
> <div markdown="1">
> - “**Modern Quantum Mechanics**” by Jun J. Sakurai and Jim Napolitano
> </div>
> </details>

**<U>Reference</U>**

Sherman, A. et al. Diamond-based microwave quantum amplifier. [Science Advances 8 (2022).](https://www.science.org/doi/10.1126/sciadv.ade6527)