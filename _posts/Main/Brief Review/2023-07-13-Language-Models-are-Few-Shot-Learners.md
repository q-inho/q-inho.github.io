---
title: "Brief Reviews on Language Models are Few-Shot Learners"
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

# Embracing Task-Agnostic Pre-Training and Robust Architectures
The rapidly advancing field of Natural Language Processing (NLP) has recently experienced significant breakthroughs, thanks to the **adoption of task-agnostic pre-training and robust architectures**. These advancements have eliminated the need for intricate fine-tuning, as evident in the impressive performance of a single pre-trained language model on standard NLP tasks

# GPT-3
**GPT-3**, an autoregressive language model equipped with 175 billion parameters, is the forefront of these advancements, exhibiting remarkable results in various settings, including zero-, one-, and few-shot on NLP tasks. As the model size expands, it has been observed that these models could evolve into more adept meta-learners, considering the growing disparity between zero-, one-, and few-shot performances as the model capacity expands.

# Pre-Training Methodologies and Learning Settings
The pre-training methodology for language models follows the foundation laid by earlier studies but incorporates **larger models and datasets**, while extending the duration of training. The exploration also includes an array of learning settings within a contextual framework, such as fine-tuning, few-shot, one-shot, and zero-shot.

# Training and Evaluating GPT-3: Process and Performance
Models have been trained using **modified versions of GPT-2 architecture** that alternate between dense and locally banded sparse attention patterns. These models vary in size, ranging from 125 million to a colossal 175 billion parameters, designed to test scaling laws. A system of partitioning models across GPUs was implemented to limit data transfer between nodes.

The training dataset was fabricated through a process of downloading and filtering CommonCrawl data, performing fuzzy deduplication, and integrating high-quality reference corpora to boost diversity. The reference corpora included an expanded version of WebText, two internet-based books corpora, and the English-language Wikipedia. Larger models necessitated smaller learning rates and larger batch sizes, guided by the gradient noise scale and trained employing model parallelism on V100 GPUs.

In the context of few-shot learning, the models evaluated examples in the evaluation set by randomly selecting K examples from the training set as conditioning. Final results were reported on the available test set or on the development set if private, due to the constraints posed by the model's size.

GPT-3 has demonstrated stellar performance in language modeling and related tasks, establishing a new state-of-the-art (SOTA) on the Penn Tree Bank dataset and achieving an 8% gain over the preceding SOTA on the LAMBADA dataset. Despite its struggle with the HellaSwag dataset, GPT-3 has shown improvement over prior zero-shot results on the StoryCloze 2016 dataset.

# GPT-3: Strengths, Shortcomings, and Future Prospects
In the domain of question-answering tasks, GPT-3 outperformed competing models on TriviaQA and matched the SOTA on open-domain QA. However, it fell short on the Natural Questions task, which tests fine-grained Wikipedia knowledge. Furthermore, GPT-3 displayed proficiency in CoQA, although it still lags behind human performance and top-tier approaches on DROP.

GPT-3's training data incorporates a blend of languages, including 7% non-English content from various internet text datasets. Few-shot GPT-3 excelled in Fr-En and De-En, outpacing the best supervised results, but it underperformed in En-Ro, attributable to GPT-2's byte-level BPE tokenizer.

SuperGLUE is a collection of standardized datasets used for few-shot learning. GPT-3 demonstrated mixed performance across tasks, nearing SOTA on COPA and ReCoRD but displaying weakness on WiC and struggles with tasks involving two-sentence comparisons.

**GPT-3's shortcomings**, including text synthesis issues like repetition, loss of coherence, and non-sequitur sentences, are notable. It also lacks bidirectional architectures and customized prediction weights, and it's not grounded in other domains of experience. Given its massive size, GPT-3 poses deployment challenges, making task-specific distillation a valuable exploration at this scale.



**<U>Reference</U>**

1. Brown, T. et al. Language models are few-shot learners. Adv. Neur. Inf. Process Sys. 33, 1877–1901 (2020).