---
title: "Brief Reviews on A Quantum Approximate Optimization Algorithm"
excerpt: ""

header:
  overlay_image: 
  overlay_filter: 

categories:
  - Brief Review
tags:
  - [Quantum Algorithm]

toc: true
toc_sticky: true
 
date: 2023-07-19
last_modified_at: 2023-07-19
---

This review is written by **non-expert** and used for **personal** study only. This post content is continuously improving.
{: .notice--danger}

The author's attention is drawn towards a remarkable quantum algorithm designed for approximate optimization. This method employs a $2n$ dimensional Hilbert space coupled with a unitary operator $U(C, \gamma)$, which is contingent on a specific angle, $\gamma$. The crux of this algorithm lies in determining the maximum value of the function Fp over a series of angles $(\gamma, \beta)$. This calculation is efficient given that p does not increase with n and that each bit partakes in no more than a fixed number of clauses.

An interesting result surfaces when assessing the mean of C(z) for strings, utilizing the calculated angles. Denoted as Mp, this mean gradually approaches the maximum of C(z) as p edges towards infinity. This is where the Fixed p Algorithm comes into play, furnishing the ability to ascertain the angles $\gamma$ and $\beta$ that maximize $F_p(\gamma, \beta)$ through classical preprocessing.

This algorithm proves potent for MaxCut problems in graphs with bounded degree, where the operator associated with an edge engages qubits within a specific distance from the edge. $F_p(\gamma, \beta)$ can be evaluated on a classical computer, where the resources do not increase with n. The quantum algorithm then generates a sample of values of C(z) ranging between 0 and +m, with the mean being $F_p(\gamma, \beta)$.

The distribution of C is largely concentrated near its mean in the state $\vert \gamma, \beta \rangle$ for fixed v and p (or p that increases slowly with n). The standard deviation of C(z) has an upper limit of order √m for fixed v and p. This suggests that the sample mean of order $m^2$ values of C(z) will be within 1 of $F_p(\gamma, \beta)$ with a high probability $(1 - 1/m)$. Moreover, the concentration of C(z)'s distribution indicates a minuscule chance for the algorithm to produce strings with C(z) exceeding $F_p(\gamma, \beta)$ by a significant margin.

Examining the quantum algorithm's application to MaxCut on 2-regular graphs (specifically, ring-shaped graphs) reveals that by increasing p, we can achieve an approximation ratio arbitrarily close to 1, irrespective of n. The circuit depth for each p can be maintained at 3p by splitting the edge sum in C into two sums over $\langle j, j + 1 \rangle$ with j being even and odd.

Further analysis on MaxCut on 3-regular graphs sheds light on the Quantum Approximate Optimization Algorithm (QAOA)'s performance. For p=1, the quantum algorithm can deliver a worst-case approximation ratio of 0.6924. Impressively, the approximation ratio attained by QAOA on any 3-regular graph is at least 0.6924 times the size of the optimal cut. The situation for p=2 is more complex but can yield an approximation ratio of 0.7559 on bipartite graphs.

The QAA identifies the optimal solution to an optimization problem, whereas QAOA procures a high-quality approximate solution. The QAOA adopts a Trotterized approximation to the evolution with small angles for each operator, while the QAA necessitates a lengthy runtime. Interestingly, as p escalates, the efficacy of QAOA improves, while the success rate of QAA does not strictly correlate with T.

A variation of the algorithm proves particularly efficient for complex search spaces, such as seeking independent sets in a graph. In this context, the Hilbert space possesses an orthonormal basis of independent sets, and the operator C is allied with a dependent unitary $U(C, \gamma)$. The quantum operator B links basis states and is linked with a dependent unitary $U(B, \beta)$. The strategy of alternating operators associated with B and C allows us to reach a state with the maximum eigenvalue and can be utilized as a subroutine for an independent set algorithm.

An innovative quantum algorithm for approximate combinatorial optimization was introduced, which employs a set of angles to produce a state and a string $z$ with an associated value C(z). There exist several methodologies for identifying an optimal set of angles, including the use of a classical preprocessor or making repeated calls to the quantum computer with different sets of angles. With a strategy for choosing sets of angles, the QAOA can be operated on a quantum computer even with p increasing with n. It holds potential for uncovering solutions to combinatorial search problems beyond the scope of classical algorithms.




**<U>Reference</U>**

1. Farhi, E., Goldstone, J. & Gutmann, S. A quantum approximate optimization algorithm (2014).