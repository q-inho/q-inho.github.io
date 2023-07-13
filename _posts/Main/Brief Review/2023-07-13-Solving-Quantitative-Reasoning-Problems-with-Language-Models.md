---
title: "Brief Reviews on Solving Quantitative Reasoning Problems with Language Models"
excerpt: ""

header:
  overlay_image: 
  overlay_filter: 

categories:
  - Brief Review
tags:
  - [Natural Language Processing]

toc: true
toc_sticky: true
 
date: 2023-07-13
last_modified_at: 2023-07-13
---

This review is written by **non-expert** and used for **personal** study only.
{: .notice--danger}

Artificial neural networks are breaking barriers across numerous fields, with an exceptional ability to tackle natural language tasks. Their prowess, however, seems to falter when it comes to **quantitative reasoning assignments** that involve complex scientific and mathematical problems.

Quantitative reasoning requires a language model to comprehend the intricacies of natural language input, retrieve factual information, and execute algorithms. As revealed by past studies, it is possible for large language models to successfully address mathematical and programming questions if they are specifically trained on domain-centric datasets.

# Minerva: Quantitative Reasoning
Among the breakthroughs in the field, Minerva stands out. This language model is designed to excel at quantitative reasoning tasks, producing solutions with accuracy and precision, employing correct LATEX notation. Minerva is rooted in the PaLM general language models and hones its skillset using a comprehensive dataset teeming with scientific and mathematical information. The model has been successful in achieving **cutting-edge results** on various datasets for mathematical and scientific queries, even in a few-shot setting.

The advent of Minerva ushers in a new era of quantitative reasoning. This is emphasized by a large dataset crafted to blend natural language with formal mathematical language, thereby setting a novel benchmark for quantitative reasoning standards. Working towards solving quantitative reasoning problems using natural language is a hot topic, with current research revealing the benefits of generating multiple solutions per problem and implementing majority voting to enhance performance.

# Approaches in Mathematical Problem-Solving
An intriguing aspect of their approach is that we investigate the **reasoning ability of the model**, rather than resorting to external libraries, as has been the case with explored code generation models. The employment of specialized programming languages allows for the simulation of formal mathematics, and language models are trained to predict mathematical expressions and guide proof searches. Furthermore, new benchmark datasets have surfaced covering advanced mathematical topics where language models encounter minimal competition from other models.

# Training and Evaluation of Language Model
Their models have been trained on a colossal dataset, composed of 38.5 billion tokens extracted from web pages with rich mathematical content and research papers from the arXiv preprint server. This includes a combination of general natural language data and mathematical expressions in MathJax format, which have undergone a meticulous cleaning process to preserve mathematical notation. Their methodology employs pretrained transformer language models, which are then further trained on a mathematical dataset using an autoregressive objective.

Their largest model, boasting 540 billion parameters, underwent finetuning on 26 billion tokens and delivered **superior performance**. The assessment was primarily centered on a few-shot evaluation using MATH and MMLU-STEM datasets. The model was able to produce a coherent solution and distinctly demarcate a final answer, evaluated using the SymPy library.

To test Minerva's scientific reasoning abilities, researchers assembled 272 STEM problems at the undergraduate level from MIT's OpenCourseWare, ensuring the solutions were verifiable. The technique of majority voting outperformed greedy decoding when selecting the right answer to a given problem. Majority voting hinges on picking the most frequently occurring answer in the modeled distribution, whereas the pass@k performance improvement originates from the tail of the distribution.

The performance of Minerva's 8B and 62B models were compared on 216 problems, with high confidence majority decisions from both models. The 8B model had dominant errors related to incorrect reasoning or calculations, while the 62B model significantly improved both reasoning and calculation robustness. Even though the false positive rate is low, it tends to rise with the difficulty level, with the pass@256 accuracy projected to be greater than 68% after accounting for false positives.

# Assessing Analytical Capability and Memorization
A key question surrounding Minerva's performance is whether it mirrors **genuine analytic capabilities or simple rote memorization**. Three analyses were carried out on the MATH dataset to gauge the extent of memorization influencing the model's performance. These results indicate minimal memorization, as there was scant evidence that the model's performance could be chalked up to rote memorization.

The study unveils a method for quantitative reasoning utilizing a language model trained on a mathematical dataset. It delivers impressive performance without the need for external tools. Limitations such as a lack of automatic verification and limited ability for complex numerical calculations exist, yet the potential societal impact, such as accessible math tutoring, is noteworthy.

**<U>Reference</U>**

1. Lewkowycz, A. et al. Solving quantitative reasoning problems with language models (2022).