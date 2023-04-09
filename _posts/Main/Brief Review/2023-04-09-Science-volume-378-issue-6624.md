---
title: "[Brief Review] Science, Volume 378 Issue 6624, 9 DEC 2022"
excerpt: "Brief Review on 'Giant electric field-induced strain in lead-free piezoceramics', 'Competition-level code generation with AlphaCode', and 'Human-level play the game of Diplomacy by combining language models with strategic reasoning' "


categories:
  - Brief Review
tags:
  - [Piezoelectrics, Computer Science]

toc: true
toc_sticky: true
 
date: 2023-04-09
last_modified_at: 2023-04-09
---

This review is written by **non-expert** and used for **personal** study only.
{: .notice--danger}

# Giant electric field-induced strain in lead-free piezoceramics
- **<U>Piezoelectrics</U>**

Piezoelectric actuators, which are devices that convert electrical energy into mechanical motion, have widespread applications in numerous industries. The market for these devices is projected to reach a value of US$35.4 billion by 2026. Despite the development of lead-free piezoelectric systems as environmentally responsible alternatives to lead-containing materials, their strain performance is often less effective. To overcome this limitation, researchers have focused on enhancing the performance of lead-free ceramics by introducing defect dipoles, which can amplify electric field-induced strain.

One promising advancement involves utilizing $V^{’}_{K/Na}$ $-V_O$ defect dipoles in a specific type of lead-free ceramic known as KNSN3. These ceramics have demonstrated extraordinary bipolar electrostrains, making them a potential substitute for lead-based piezoelectric ceramics in actuator applications. The bipolar electrostrains of KNSN3 ceramics are 1.05% at room temperature and 1.67% at 160°C, which are significantly higher than those of typical lead-free ceramics.

To comprehensively understand the crystal structure and performance of these ceramics, scientists employed X-ray diffraction patterns. This technique provides insight into the arrangement of atoms within a material, allowing researchers to investigate the composition dependence of KNSN ceramics. They ascertained that doping the ceramics with a chemical element called strontium ($Sr$) has a substantial impact on their properties. Elevated concentrations of strontium led to augmented lattice symmetry and weaker ferroelectricity, which is the capacity of a material to exhibit a spontaneous electric polarization that can be reversed by an external electric field.

KNSN3 ceramics are recognized to have vacancies of potassium ($K+$), sodium ($Na+$), and oxygen. These vacancies are common in KNN-based ceramics and can affect their performance. Strontium was discovered to diminish the concentration of oxygen vacancies in the ceramics, influencing their strain behavior. When contrasting the strain behavior of KNSN3 ceramics to a prevalent lead-based material named PZT, the KNSN3 samples exhibited unique properties ascribed to defect dipoles and domain switching. Domain switching refers to the reorientation of regions with uniform polarization, called domains, within a ferroelectric material under an electric field.

The strain behavior of KNSN3 ceramics can be elucidated by the interaction between aligned defect dipoles and domain switching. This interaction results in additional lattice stretching or contraction under an external field beyond what is observed in regular ferroelectric materials. The strain curve exhibits a specific pattern, with a rapidly descending segment succeeded by a slowly descending segment. This pattern indicates the complex interplay between the ferroelectric domains and defect dipoles within the material.

The polarization stability in KNSN3 ceramics was found to be high, and the ceramics displayed remarkable fatigue resistance and thermal stability. These properties render them an attractive candidate for replacing lead-based piezoelectric ceramics in an array of applications, particularly high-temperature actuators. The microstructure of KNSN3 ceramics exhibits three different morphological features, including stripe domains, nanosized domains, and mixed domains. Inhomogeneous distribution of $K$ and $Na$ elements is observed in KNSN3 ceramics, which affects their performance.

Furthermore, KNSN3 ceramics demonstrate enhanced electric field-induced strain at temperatures exceeding 100°C, with peak strains achieved at 160°C, making them suitable for high-temperature actuator applications. This improved strain is due to the coupling of defect dipoles with ferroelectric domains, which can be tailored by adjusting the $V^{’}_{K/Na}$ $-V_O$ defect dipoles and microstructure. KNSN3 ceramics exhibit high unipolar strain performance, excellent fatigue resistance, and thermal stability, making them a potential lead-free alternative for high-displacement piezoelectric actuator applications. The enhanced strain at higher temperatures is particularly important for devices that need to operate in environments with elevated temperatures, such as automotive or aerospace applications.

In situ **transmission electron microscopy** (TEM) results show lattice evolution under an electric field in nanosized and stripe domain regions, providing valuable insights into the material's behavior at the atomic level. The lattice parameters in pure nanosized domain grain decrease under positive electric stimuli and increase under negative stimuli. The multiphase coexistence in nanosized domain regions allows for fixed polarization alignment with defect dipoles, further contributing to the material's superior performance.

The aging process does not enhance the electrostrain value of KNSN3 ceramics, indicating that all defect-dipole alignments are achieved in the first application of the electric field. This finding suggests that KNSN3 ceramics can maintain their performance over time, making them a durable and reliable choice for various applications.

KNSN3 ceramics showcase promising properties for piezoelectric actuator applications due to their high strain performance, thermal stability, and environmentally friendly composition. By modifying the defect dipoles and microstructure, researchers can tailor the properties of these ceramics for specific applications, potentially establishing them as a viable lead-free alternative to traditional piezoelectric materials. This development holds immense potential for the future of environmentally conscious, high-performance piezoelectric devices in various industries.


>**Required Additional Study Materials**
> 
> - P. Fan, K. Liu, W. Ma, H. Tan, Q. Zhang, L. Zhang, C. Zhou, D. Salamon, S.-T. Zhang, Y. Zhang, B. Nan, H. Zhang, Progress and perspective of high strain NBT-based lead-free piezoceramics and multilayer actuators. J. Materiomics 7, 508–544 (2021).
> - J. Hao, W. Li, J. Zhai, H. Chen, Progress in high-strain perovskite piezoelectric ceramics. Mater. Sci. Eng. Rep. 135, 1–57 (2019).
> - M. Waqar, H. Wu, J. Chen, K. Yao, J. Wang, Evolution from lead-based to lead-free piezoelectrics: Engineering of lattices, domains, boundaries, and defects leading to giant response. Adv. Mater. 34, 2106845 (2021).
> <details>
> <summary>Introductory material</summary>
> <div markdown="1">
> - “**Piezoelectric Ceramics: Principles and Applications**” by APC International Ltd
> </div>
> </details>

**<U>Reference</U>**

Haungfu, G. et al. Giant electric field–induced strain in lead-free piezoceramics. [Science 378, 1125-1130 (2022).](https://www.science.org/doi/10.1126/science.ade2964)

-----

# Competition-level code generation with AlphaCode
- **<U>Computer Science</U>**

Creating code from problem descriptions is a complex task in computer science, and until now, success has been mostly limited to specific areas or short code segments. Examples of program synthesis, which is the process of automatically generating code, include tools like Flash Fill and code completion tools. These tools enhance productivity in data entry and programming tasks by predicting and automatically completing parts of the code based on context.

Recent advancements in transformer-based language models, which are advanced machine learning models, have made it possible to tackle simple programming issues with minimal modifications. However, generating entire programs demands a deeper understanding of the problem at hand and figuring out the right algorithm to use. **Competitive programming** represents a significant leap in assessing a computer system's intelligence, as it involves understanding complex natural language descriptions, mastering a wide range of algorithms and data structures, and accurately implementing solutions that can span hundreds of lines.

AlphaCode is a state-of-the-art code generation system that can solve $29.6\%$ of competitive programming problems, using up to 10 submissions per problem. It outperforms previous models by increasing the number of model samples, or potential solutions, it generates. In simulated programming competitions, AlphaCode achieved an average ranking within the top $54.3\%$ of human participants, making it the first computer system to reach such a competitive level.

The researchers, designed a learning system to address the challenges of competitive programming. These challenges include searching within a vast program space, having limited access to example tasks, and being restricted in the number of submissions allowed per problem. The system utilizes a transformer architecture, which is a type of machine learning model, to predict solutions to problems given a natural language description. It then generates corresponding solutions in a programming language, taking into account the context and requirements of the problem.

The models were initially trained on a large dataset of human-written code from GitHub and then fine-tuned on a smaller dataset of competitive programming problems called CodeContests. During fine-tuning, the natural language problem statement was included as a program comment, and various models with different numbers of parameters were trained, ranging from 300 million to 41 billion.

The research paper proposes several enhancements to the transformer encoder-decoder architecture, which is the **underlying structure of the model**, to improve the rate at which problems are solved. These improvements include techniques such as **multi-query attention**, **masked language modeling**, **tempering**, **value conditioning** and **prediction**, and generation by off-policy learning from demonstrations. To ensure a diverse set of potential solutions, the researchers used a high temperature and conditioning on random metadata during the sampling process. They then applied filtering and clustering techniques to select the 10 best samples for submission based on program behavior.

AlphaCode was tested against programming competitions from the Codeforces platform to assess its performance. The evaluation was done using ensembled models with varying numbers of parameters, simulating AlphaCode in a live competitive environment. It achieved an average ranking in the top $54.3\%$ and solved $66\%$ of problems with the first submission, making it competitive with human participants in programming competitions.

The study analyzed the models' strengths and weaknesses in solving problems by exploiting structural weaknesses in the problem itself. The models did **not** copy the core logic from the training data and had higher success rates for problems that dealt with bitmasks, sorting, greedy algorithms, or math. However, they had lower success rates for dynamic programming, constructive algorithms, and graph problems, indicating areas for potential improvement.

AlphaCode showed sensitivity to changes in problem descriptions, indicating its ability to adapt to different tasks. Modifications to the problem statement significantly decreased the correctness of generated samples, while AlphaCode could mostly ignore minor alterations that did not fundamentally change the problem. This adaptability is a key feature that allows the system to be more versatile in addressing a wide range of programming challenges and scenarios.

AlphaCode is a cutting-edge system that generates new solutions to programming problems and performs at a competitive level on the Codeforces platform. Its success can be attributed to the use of transformer models and a well-prepared dataset, which enable it to learn from a vast collection of human-written code and apply that knowledge to solving competitive programming problems.


>**Required Additional Study Materials**
> 
> <details>
> <summary>Introductory material</summary>
> <div markdown="1">
> - “**The Pragmatic Programmer: From Journeyman to Master**” by Andrew Hunt and David Thomas
> - “**Code Complete: A Practical Handbook of Software Construction**” by Steve McConnell
> </div>
> </details>

**<U>Reference</U>**

Li, Y. et al. Competition-level code generation with AlphaCode. [Science 378, 1092-1097 (2022).](https://www.science.org/doi/10.1126/science.abq1158)

-----

# Human-level play in the game of Diplomacy by combining language models with strategic reasoning
- **<U>Computer Science</U>**

Achieving human-level performance in AI agents capable of planning, coordinating, and negotiating with humans using natural language is a crucial long-term objective in artificial intelligence. Cicero, an AI agent demonstrating such performance in the strategy game Diplomacy, incorporates a controllable dialogue module and a strategic reasoning engine to anticipate other players' actions and facilitate mutually beneficial coordination.

Although self-play has led to AI breakthroughs in 2p0s games, cooperative games may not perform well with humans without human data. Diplomacy, which necessitates precise planning, lengthy dialogue histories, and human-interpretable communication, challenges players to establish trust in a distrustful environment. In Diplomacy, seven players strive to control supply centers on a map, with victory going to the player who controls the majority.

Cicero integrates a dialogue module, strategic reasoning module, and a filtering process to eliminate low-quality messages. The dialogue, generated by a pretrained language model, is controllable through intents and is further trained on human Diplomacy game data. Cicero employs strategic reasoning to predict player policies and choose optimal actions, utilizing a planning algorithm and a value/policy function trained via self-play reinforcement learning.

The researchers used a dataset of 125,261 Diplomacy games from webDiplomacy.net, with 40,408 games containing dialogue and a total of 12,901,662 messages. They trained a neural generative Diplomacy dialogue model, controllable through intents, using the R2C2 model as a base. The model predicted dialogue messages based on factors such as dialogue history, game state, action history, player rating, and intents.

Controllable through intents specified by the strategic reasoning module, the dialogue model generates higher-quality messages. The model learns the distribution of intents during training, offering control over generation during inference. However, richer intents are more challenging to annotate and select, increasing the risk of taking the language model out of distribution.

Annotated intents were used to closely mirror message content, resolving issues related to dishonest messages or changing plans. Annotated intents achieved a $97\%$ correspondence between action and content in a small test set. During gameplay, Cicero selects intent actions for the current turn using strategic reasoning and a human-imitation model for future turns. The dialogue model surpassed baselines and demonstrated improved perplexity and higher-quality, consistent messages.

Cicero uses strategic reasoning to predict player policies and choose optimal actions in Diplomacy, incorporating piKL and its generalization, **DiL-piKL**, to model other players' policies. Cicero accounts for players' ability to correlate actions through private dialogue, using piKL to predict policies based on dialogue and board state, and training a human-compatible state value function through self-play reinforcement learning with CoShar piKL.

Neural language models often generate **inconsistent** and **incorrect information**, which the researchers addressed by **filtering messages** using classifiers and checks. Filters included discriminating between human and counterfactual text, intent correspondence, and value-based filtering.

Cicero anonymously participated in 40 webDiplomacy.net Diplomacy games, ranking in the top $10\%$ and winning an eight-game tournament. Cicero's AI status was revealed at the research's conclusion. Combining strategic reasoning and dialogue, Cicero achieved strong human-level performance, successfully passing as a human player without arousing suspicion from other players.

Cicero's success demonstrates the potential for AI agents to cooperate and negotiate with humans effectively in complex environments. Despite occasional mistakes, Cicero's human-like performance did not raise suspicions among the other players, suggesting that AI agents can effectively blend into human social settings.

The development of AI agents like Cicero offers numerous possibilities for practical applications. These agents could be utilized in various collaborative settings, such as negotiations, decision-making, and team-based problem-solving, where maintaining trust and understanding human dynamics is crucial.

Moreover, Cicero's accomplishments highlight the importance of incorporating both strategic reasoning and controllable dialogue in AI development. By using intents and filtering processes, AI agents can generate higher-quality, more consistent messages, enhancing their ability to cooperate with humans.

Future research can build upon Cicero's success by exploring other domains where human cooperation and negotiation are essential. Additionally, researchers can investigate ways to improve the controllability of AI-generated dialogue, further refining the performance of AI agents in complex social environments.

Cicero's achievements in the game of Diplomacy serve as a stepping stone for the development of AI agents capable of human-level performance in cooperation and negotiation. By combining strategic reasoning and controllable dialogue, AI agents like Cicero have the potential to revolutionize collaborative environments and contribute to a wide range of practical applications.



>**Required Additional Study Materials**
> 
> - M. Campbell, A. J. Hoane Jr., F. Hsu, Deep Blue. Artif. Intell. 134, 57–83 (2002).
> - T. Hiraoka, G. Neubig, S. Sakti, T. Toda, S. Nakamura, Construction and analysis of a persuasive dialogue corpus, in Situated Dialog in Speech-Based Human-Computer Interaction (Springer, 2016)
> <details>
> <summary>Introductory material</summary>
> <div markdown="1">
> - “**Language Models in Plain English**” by Austin Eovito and Marina Danilevsky
> </div>
> </details>

**<U>Reference</U>**

Meta Fundamental AI Research Diplomacy Team (FAIR), et al. Human-level play in the game of Diplomacy by combining language models with strategic reasoning. [Science 378, 1067-1074 (2022).](https://www.science.org/doi/10.1126/science.ade9097)