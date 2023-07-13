---
title: "Brief Reviews on Carbon Emissions and Large Neural Network Training"
excerpt: ""

header:
  overlay_image: 
  overlay_filter: 

categories:
  - Brief Review
tags:
  - [Natural Language Processing, Cloud Computing, Carbon Emissions]

toc: true
toc_sticky: true
 
date: 2023-07-13
last_modified_at: 2023-07-13
---

This review is written by **non-expert** and used for **personal** study only.
{: .notice--danger}

# Energy Demands of Machine Learning Models
As the **scale and complexity** of machine learning (ML) models expand, the associated energy demands are escalating, resulting in considerable environmental impact. A crucial area for exploration and discussion lies in the energy consumption and carbon dioxide equivalent (CO2e) emissions of contemporary, large-scale Natural Language Processing (NLP) models.

The energy usage and carbon footprint of an ML model depend on an array of elements, such as the chosen algorithm, software programming, processor capabilities, the efficiency of the datacenter, and the source of the energy supply. Interestingly, the process of inference – where new data is fed into a trained model to make predictions – consumes more energy than training the model. This has led to the development of ML accelerators specifically engineered for inference tasks.

A promising approach to lessen the environmental impact lies in optimizing ML models and infrastructure. The authors make a compelling argument for changing publication norms for energy-intensive ML models. They encourage calculating CO2e emissions, evaluating the efficiency of models, and publishing information on training duration and accelerator usage. These steps could generate a beneficial cycle where increased accuracy is balanced with decreased energy consumption and CO2e emissions for ML models.

# Energy Efficiency
For example, the Transformer model's environmental impact can be considerably reduced by choosing the right deep neural network (DNN) model, processor, datacenter, and geographical location. Specifically, the Evolved Transformer model stands out for its superior efficiency, requiring fewer floating point operations per second (FLOPS) and less time compared to the Transformer (Big) model, while still maintaining comparable accuracy.

Advanced technologies are instrumental in improving the energy efficiency of ML models. Google's custom TPU v2 processor, for example, executes the Transformer (Big) and Evolved Transformer (Medium) models at a quicker pace and with reduced power consumption, thus improving cost-performance and performance per Watt.

# Datacenters and Cloud Computing in Energy Efficiency
The efficiency of a datacenter can be quantified using the Power Usage Effectiveness (PUE) ratio. Notably, cloud datacenters are roughly twice as energy efficient as enterprise datacenters. Google's Iowa datacenter, with a PUE of 1.11, outperforms the US national average by approximately 40%.

Cloud companies are stepping up to the plate in prioritizing energy efficiency as a means to cut costs and reduce emissions. Google, for instance, aims to power all its datacenters and offices with carbon-free energy around the clock by 2030. Its clean energy portfolio has substantially reduced the net CO2e per kWh of its Iowa datacenter by a factor of 5.4 compared to the US average.

Even with a 550% increase in computing capacity between 2010 and 2020, global datacenter energy consumption rose by only 6%. This can be attributed in part to the energy efficiency of cloud datacenters.

ML researchers can actively influence the carbon footprint of their models through careful selection of the DNN model, processor, and datacenter. Various tools are available, like the ML Emissions Calculator or the Green Algorithms tool, which can be used to estimate a datacenter's CO2e emissions.

An analysis was conducted on the CO2e emissions of five prominent NLP models: T5, Meena, GShard, Switch Transformer, and GPT-3. The energy used in training these models varied from 9 to 232 MWh, resulting in CO2e emissions ranging between 4.3 and 96 tCO2e.

Implementing higher standards for measuring and documenting ML model energy requirements could provide a clearer understanding of the trade-offs between cost and accuracy. This could potentially lead to a reduction in overall emissions. Training ML models requires resources beyond just the final training run. It can be challenging to account accurately for these costs, but tools like the experiment-impact-tracker and ML Emissions Calculator can assist in this effort.

Algorithmic techniques can enhance energy efficiency in ML models by reducing computational costs and carbon emissions. Techniques like distillation, pruning, quantization, efficient coding, fine-tuning, transfer learning, and sparsely activated mixture-of-expert-style models can accomplish comparable accuracy with reduced computation and energy expenditure.

# Balancing Societal Benefits and Environmental Responsibility in Machine Learning
Choosing the right datacenter for training a DNN can substantially impact its carbon footprint. The rise of cloud computing has made energy-optimized datacenters available to individuals globally through services like Alibaba Cloud, Amazon Web Services, Google Cloud Platform, and Microsoft Azure.

With the popularity of the public cloud growing by up to 50% annually since 2010, it is believed to be the future of all datacenters. In terms of carbon footprint, training large NLP models pales in comparison to activities like air travel and Bitcoin mining.

NLP models offer societal benefits, such as COVID-19 Research Explorer and improved search results in multiple languages. Google's GShard multilingual translation model, for instance, has been used to translate billions of queries annually for languages with limited resources.

The ML community must strive to reduce its carbon emissions and enhance energy efficiency in algorithms, datacenters, hardware, and software. Suggestions for this include publishing energy consumption and CO2e data, incentivizing efficiency improvements, and including training costs in academic publications.

**<U>Reference</U>**

1. Patterson, D. et al. Carbon emissions and large neural network training (2021).