---
title: "Brief Reviews on Classification with Quantum Neural Networks on Near Term Processors"
excerpt: ""

header:
  overlay_image: 
  overlay_filter: 

categories:
  - Brief Review
tags:
  - [Quantum Algorithm, Quantum Nneural Networks]

toc: true
toc_sticky: true
 
date: 2023-07-22
last_modified_at: 2023-07-22
---

This review is written by **non-expert** and used for **personal** study only. This post content is continuously improving.
{: .notice--danger}

**Quantum Neural Networks** operate on a **quantum processor** that manipulates **quantum bits** or **qubits** through **unitary transformations**. These networks aim to accurately predict the **labels** of unseen data instances. To determine the labels, a QNN employs a **readout qubit** and calculates a **Pauli operator**. The anticipated label's value reflects the average of the outcomes observed. The network's parameters are **fine-tuned** during the **learning phase** to minimize **sample loss**, employing a quantum processor to pinpoint the optimal parameters.

The **learning procedure** in a QNN is designed to generalize to unseen instances. It doesn't explicitly introduce non-linearities but employs **parameterized unitaries**. These unitaries take the form $exp(i\theta \sum )$, with $\sum$ being a generalized Pauli operator. **Stochastic gradient descent** is used to revise the parameters, grounding on the loss from training instances.

The gradient of the loss function relative to the parameters remains bounded by the number of parameters, mitigating the "**gradient blow-up**" phenomenon often seen in classical neural networks. The technique of using unitary transformations to control this phenomenon has been examined in classical machine learning and naturally arises in the quantum context.

The QNN can express any **two-valued label function**, but at a significant **circuit depth cost**. A **Reed-Muller formula**, which can exponentially elongate, can represent the label function. The quantum representation outcome shares similarities with the classical representation theorem, opening avenues for further exploration in compactly representing functions on a quantum circuit.

The Reed-Muller formula can also depict **subset parity**, the parity of a subset of bits, requiring a unitary circuit with at most n commuting two-qubit operators. On the other hand, **subset majority**, depicted using the z variables, labels 1 if the majority of bits in the subset are 1. This label can be written as a sign function of the sum of the subset bits. For subset majority, the unitary involves the Z and X operators and can attain perfect categorical error through repeated Yn+1 measurements.

Two strategies can be employed to alter the parameters $\overrightarrow{θ}$ to minimize sample loss. The first strategy comprises estimating the sample loss and computing the gradient of the sample loss concerning $\overrightarrow{θ}$. The second strategy involves calculating the gradient utilizing the derivative of the sample loss concerning $\theta _k$. The **unitary operator** $U(\overrightarrow{\theta})$ is leveraged to reexpress the sample loss and measure the gradient. An accurate gradient estimate is required to update $\overrightarrow{\theta}$.

QNNs have been tested on real-world data, such as a downsampled version of the **MNIST dataset**, which focuses on differentiating digits 3 and 6. Initially, the quantum classifier employed a limited set of one and two-qubit unitaries, resulting in a categorical error of 10%. By restricting the gate set to ZX and XX, the QNN reduced the categorical error to 2%. These results demonstrate that while QNNs can classify real-world data, the datasets employed could also be classified easily by a classical network. Further refinement is necessary to enhance the QNN's performance.

The next phase of QNN development involves an exploration of **gate sets** and refining the quantum neural network to augment its performance. Two strategies are proposed for **batch learning** in quantum neural networks. The first strategy combines samples into superposition states. In contrast, the second strategy computes the gradient one sample at a time and averages the gradients.

The **empirical risk** of the whole sample space in a quantum neural network can be minimized by discovering parameters that satisfy equation

$$
1 - \frac{1}{2} \left( \langle + 1 \vert U^{\dagger}(\overrightarrow{\theta})Y_{n+1}U(\overrightarrow{\theta}) \vert + 1 \rangle - \langle - 1 \vert U^{\dagger}(\overrightarrow{\theta})Y_{n+1}U(\overrightarrow{\theta}) \vert - 1 \rangle \right)

$$

 equal to 0. Learning with **quantum batches** proved more effective than learning with individual sample states, showing a smoother decrease in empirical risk and requiring less sample complexity.




**<U>Reference</U>**

1. Farhi, E. & Neven, H. Classification with quantum neural networks on near term processors (2018).