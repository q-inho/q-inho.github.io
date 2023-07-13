---
title: "Brief Reviews on Deep Learning"
excerpt: ""

header:
  overlay_image: 
  overlay_filter: 

categories:
  - Brief Review
tags:
  - [Deep Learning, Mathematics and Computing, Computer Science]

toc: true
toc_sticky: true
 
date: 2023-07-13
last_modified_at: 2023-07-13
---

This review is written by **non-expert** and used for **personal** study only.
{: .notice--danger}

# The Evolution from Conventional to Deep Learning
Deep learning, a subset of machine learning, is increasingly becoming the cornerstone of modern technological applications. Its use spans a wide range of tasks, from enhancing internet searches to fine-tuning content filtering and recommendations. This technology leverages layered non-linear transformations, allowing machines to learn complex functions with minimal manual intervention.

Traditionally, machine learning models required meticulous crafting to transform raw data into an optimal representation suitable for analysis or classification. However, the evolution of learning mechanisms has revolutionized this process, introducing automated methods of data interpretation.

# Representation Learning and Supervised Learning
Representation learning algorithms automatically distill the necessary representations from raw data required for detection or classification tasks. Among the various types of representation learning, deep learning has emerged as a particularly promising approach. It utilizes multiple non-linear transformations to decipher complex functions and has demonstrated commendable performance across various sectors. Furthermore, the minimal engineering requirement of deep learning enables it to harness the power of computational advancements and data influx effectively.

Among the various methodologies used in machine learning, supervised learning is the most prevalent. This method trains a machine to classify images or other data types using labeled data. When combined with deep learning, it enables the creation of computational models with multiple layers that can learn data representations at different levels of abstraction.

# Optimization and the Power of Deep Learning
A pivotal step in the learning process involves adjusting weight vectors to minimize output error. One common method employed to achieve this is the stochastic gradient descent. This optimization technique iteratively adjusts weights based on small subsets of the training set until the objective function ceases to decrease.

Problems such as image and speech recognition require sensitivity to minute input variations, which traditional linear classifiers, with their simplicity, struggle to address. Deep learning, with its inherent capability to automatically learn useful features, offers a solution. It does so by stacking simple modules in multilayers, which enhances both the selectivity and invariance of the representation.

Multilayer networks, which lie at the heart of deep learning, can be trained using a method called backpropagation. This technique computes gradients by working backwards from the output to the input, simplifying the calculation of gradients with respect to the weights of each module.

# Convolutional Neural Networks (ConvNets) and Their Impact
The application of deep learning methodologies extends to feedforward neural networks, especially those that employ Rectified Linear Unit (ReLU) non-linear functions for faster learning. Convolutional Neural Networks (ConvNets), a type of deep learning model, are notable for their ability to process data in the form of multiple arrays like images or audio spectrograms.

ConvNets have gained prominence in tasks requiring vast labeled data, such as traffic sign recognition and face detection. Their success in the ImageNet competition in 2012 revolutionized the field, making them the go-to approach for most recognition and detection tasks.

The progress in hardware, software, and algorithm parallelization has allowed training complex ConvNet architectures within a few hours. Major tech companies and startups have initiated research and development projects and deployed ConvNet-based image understanding products and services.

Deep nets, owing to their ability to learn distributed representations, hold an exponential advantage over classic learning algorithms. Composing layers of representation in a deep net unlocks another potential exponential advantage.

Recurrent Neural Networks (RNNs) are highly effective for sequential inputs. They can predict the next character or word and are even applied in complex tasks like machine translation.

# The Future of Deep Learning
In the long term, unsupervised learning is expected to gain prominence, as it emulates human and animal learning more closely. The fusion of deep learning with reinforcement learning and selective attention strategies could lead to significant advancements in artificial intelligence.


**<U>Reference</U>**

1. LeCun, Y., Bengio, Y. &amp; Hinton, G. Deep learning. Nature 521, 436–444 (2015). 