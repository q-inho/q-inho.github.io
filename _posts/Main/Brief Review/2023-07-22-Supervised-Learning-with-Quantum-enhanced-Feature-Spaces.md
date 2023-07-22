---
title: "Brief Reviews on Supervised Learning with Quantum-enhenced Feature Spaces"
excerpt: ""

header:
  overlay_image: 
  overlay_filter: 

categories:
  - Brief Review
tags:
  - [Quantum Algorithm, Quantum Machine Learning]

toc: true
toc_sticky: true
 
date: 2023-07-22
last_modified_at: 2023-07-22
---

This review is written by **non-expert** and used for **personal** study only. This post content is continuously improving.
{: .notice--danger}

The **complexity** associated with **quantum computing** can be effectively managed by deploying **short-depth circuits**. Notably, these circuits have demonstrated compatibility with **noisy devices** while effectively reducing **decoherence** through **error-mitigation techniques**. However, the challenge lies in simulating these simple circuits using **classical computational methods**.

To overcome this, the focus has shifted towards **supervised learning** and developing **classifiers**, specifically designed for quantum computing.

Classically, problems in this space are tackled using **support vector machines (SVMs)**. However, proposals have now emerged for a **quantum version of SVMs**, designed to handle data in a **coherent superposition**.

By embracing a quantum perspective, **two binary classifiers** have been put forward that can process data supplied in a **classical format**. Uniquely, these classifiers utilize the **quantum state space** as a **feature space**, achieving remarkable results. A proof of concept implementation on a **superconducting quantum processor** was able to classify data with a remarkable **100% success ratio**.

For conventional SVMs, efficiency in training and classification is attained when the **inner products between feature vectors** can be effectively evaluated. However, **quantum circuits** do not hold a quantum advantage over conventional SVMs if the **feature vector kernel** can be efficiently computed on a classical computer.

To gain an edge over classical approaches, there is a pressing need for a **feature map** grounded in circuits that pose significant challenges to classical simulation.

A circuit exhibiting excellent performance in trials and not overly complex is employed to define a feature map on **n-qubits**. The circuit is activated on the **initial state**, utilizing the coefficients to **encode the data**.

While it is **#P-hard** to evaluate the inner product between two states originating from a similar circuit, simulation of a **single-layer preparation circuit** can be efficiently achieved classically.

The **quantum variational classification protocol** consists of four primary steps: first, **mapping data to a quantum state**; second, applying a **short-depth quantum circuit to the feature state**; third, performing a **binary measurement for classification**; and finally, making a decision based on **repeated measurements**.

The optimization is executed by defining a **cost function** that is predicated on the **error probability** of incorrectly assigning a label from the **empirical distribution**. This **empirical risk** is calculated by averaging the error probability across the full training set.

The entire process entails two phases: **training the classifier and optimizing the parameters**, followed by employing the classifier to **assign labels to unlabelled data**.

The successful implementation of the **quantum variational classifier** on a **superconducting quantum processor** was achieved for different depths, with the anticipation of higher classification success correlating with increased depth. The binary measurement was derived from the **parity function**, $f = Z_1Z_2$, and the data was generated from three different random unitaries for each depth.

Furthermore, the **optimization of the empirical risk** was displayed for various training sets and depths, applying an **error mitigation technique** based on **zero-noise extrapolation**.

The **quantum state space** plays a vital role as it can be interpreted as a feature space with **vectors** and **inner products**. The trace signifies the **Hilbert-Schmidt inner product** between the normal vector and the mapped datum.

This protocol is remarkable as it employs a quantum computer twice: first to **estimate the kernel** for all pairs of training samples, and then to estimate the kernel for a new datum in the **classification phase**. The convergence of this method and the classification results have been successfully demonstrated, leading to the successful classification and **convergence of the cost function**.

The study underlines the significance of **feature maps** that are hard to estimate using classical methods. This difficulty is a key component in establishing a **quantum advantage** and hints at the possibility of extending the technique beyond **binary classification**.



**<U>Reference</U>**

1. Havlíček, V. et al. Supervised learning with quantum-enhanced feature spaces. Nature 567, 209–212 (2019). 