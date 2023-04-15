---
title: "Brief Reviews of Nature Machine Intelligence: Volume 4, Issue 1 (January, 2022)"
excerpt: "Brief Review on 'Neurons learn by predicting future activity' "

header:
  overlay_image: /assets/images/Nature_Machine_Intelligence_Journal.png
  overlay_filter: rgba(2, 115, 94, 0.7)

categories:
  - Brief Review
tags:
  - [Learning Algorithm]

toc: true
toc_sticky: false
 
date: 2023-04-16
last_modified_at: 2023-04-16
---

This review is written by **non-expert** and used for **personal** study only.
{: .notice--danger}

## Neurons learn by preidicting future activity
- **<U>Learning Algorithm</U>**

### Take home message
- Understanding how the brain learns could lead to machines with human-like intellectual capacities.
- A single neuron's ability to predict its future activity may provide an effective learning mechanism, derived from a metabolic principle that neurons need to minimize their own synaptic activity while maximizing their impact on local blood supply by recruiting other neurons.
- This mathematically derived learning rule can provide a theoretical connection between diverse types of brain-inspired algorithms, and could be an important missing element to understand computation in the brain, with potential implications for the development of a general theory of neuronal learning.

### Bridging the Gap in Neuroscience through Predictive Learning 

Currently, neuroscience lacks a comprehensive, unifying theory to explain brain function. By studying deep neural networks, we can gain insights that may help us develop a predictive learning rule. This learning rule connects various brain-inspired algorithms and brings us a step closer to a unified theory of neuronal learning, all while focusing on maximizing a cell's energy efficiency.

### Neurons and Their Predictive Learning Capabilities 

The brain functions as a system that makes predictions, but the mechanisms behind this are not well understood. Some researchers propose that specific neuronal circuits involve "error units," but the authors of this study suggest an alternative: a **predictive model within individual neurons**. By modifying a temporal difference learning algorithm to be more biologically plausible, they propose a predictive learning rule that allows for the construction of different predictive brain systems using single neurons as building blocks.

### Adapting the Learning Algorithm for a Realistic Brain Function 

The contrastive Hebbian learning algorithm presents challenges due to its requirement for steady-state equilibrium in two separate learning phases, which is unlikely to occur in a real brain. The authors suggest combining both activity phases into one, drawing inspiration from sensory processing in the cortex. Here, the initial bottom-up activity is sufficient for neurons to predict the steady-state part of the free-phase activity. The difference between the predicted free phase and the clamped phase can then be used to adjust synaptic weights, which are essential for learning.

### Streamlining the Synaptic Plasticity Rule and Testing the Predictive Learning 

Rule The equation for neuron activity requires knowledge of all presynaptic neuron activity, which may not be realistic. The authors propose using actual presynaptic activity instead of predicted activity to simplify the synaptic plasticity rule. This rule adjusts synaptic weights by comparing actual and predicted activity. To test the predictive learning rule, the authors examined various biologically inspired network architectures and found it to be effective in tasks such as handwritten digit recognition.

The proposed predictive learning rule offers a new theoretical perspective on neuronal learning derived from basic cellular principles. This study marks the first time a synaptic learning rule has been developed from these principles, suggesting that traditional neuronal models might be too simplistic to capture the computational properties of biological neurons. Although there are limitations due to current technology, this model presents a theoretical connection between various brain-inspired algorithms and could lead to a better understanding of neuronal principles.



>**Required Additional Study Materials**
>
> - Rumelhart, D. E., Durbin, R., Golden, R. & Chauvin, Y. in Backpropagation: Theory, Architectures and Applications (eds Chauvin, Y. & Rumelhart, D. E.) 1–34 (Psychology Press, 1995).
> - Magee, J. C. & Grienberger, C. Synaptic plasticity forms and functions. Ann. Rev. Neurosci. 43, 95–117 (2020).
> - Buzsáki, G. The Brain from Inside Out (Oxford Univ. Press, 2019).
> - Rao, R. P. & Ballard, D. H. in Neurobiology of Attention (eds Itti, L. et al.) 553–561 (Elsevier, 2005).
> - Kandel, E. R., Schwartz, J. H. & Jessell, T. M. Principles of Neural Science (McGraw-Hill, 2000).
> - Almeida, L. B. A learning rule for asynchronous perceptrons with feedback in a combinatorial environment. In Artificial Neural Networks: Concept Learning (ed. Diederich, J.) 102–111 (ACM, 1990).
> - LeCun, Y. & Bengio, Y. Convolutional networks for images, speech, and time-series. In The Handbook of Brain Theory and Neural Networks (ed. Arbib, M. A.) 3361 (MIT Press, 1995).
> - Krizhevsky, A. & Hinton, G. Learning Multiple Layers of Features from Tiny Images Technical Report TR-2009 (Univ. Toronto, 2009).
> - Luczak, A. & MacLean, J. N. Default activity patterns at the neocortical microcircuit level. Front. Integrative Neurosci. 6, 30 (2012).
> - Raichle, M. E. & Mintun, M. A. Brain work and brain imaging. Annu. Rev. Neurosci. 29, 449–476 (2006).
> - Harris, J. J., Jolivet, R. & Attwell, D. Synaptic energy use and supply. Neuron 75, 762–777 (2012).
> - Hebb, D. O. The Organization of Behavior: A Neuropsychological Theory (Wiley, 1949).
> - Buzsáki, G. & Draguhn, A. Neuronal oscillations in cortical networks. Science 304, 1926–1929 (2004).
> - Buzsaki, G. Rhythms of the Brain (Oxford Univ. Press, 2006).
> - Luczak, A. in Analysis and Modeling of Coordinated Multi-Neuronal Activity (ed. Tatsuno, M.) 163–182 (Springer, 2015).
> - Harris, K. D., Quiroga, R. Q., Freeman, J. & Smith, S. L. Improving data quality in neuronal population recordings. Nat. Neurosci. 19, 1165–1174 (2016).
> - Duchi, J., Hazan, E. & Singer, Y. Adaptive subgradient methods for online learning and stochastic optimization. J. Mach. Learn. Res. 12, 2121–2159 (2011).
> <details>
> <summary>Introductory material</summary>
> <div markdown="1">
> - **“Principles of Neural Science”** by Eric Kandel, James Schwartz, and Thomas Jessell
> - **“The Predictive Mind”** by Jakob Hohwy
> - **“Deep Learning”** by Ian Goodfellow, Yoshua Bengio, and Aaron Courville
> - **“Pattern Recognition and Machine Learning”** by Christopher Bishop
> </div>
> </details>

**<U>Reference</U>**

Luczak, A., McNaughton, B.L. & Kubo, Y. Neurons learn by predicting future activity. [Nat Mach Intell 4, 62–72 (2022). ](https://doi.org/10.1038/s42256-021-00430-y)

