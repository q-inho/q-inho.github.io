---
title:  "Study Roadmap for Computer Science"
excerpt: "Software Engineering, Network, AI and others.."

categories:
  - comp-general
tags:
  - [Physics]

toc: false
toc_sticky: false
 
date: 2022-09-18
last_modified_at: 2022-09-18
---

# My Roadmap for Computer Science


<div class="mermaid"> 
      graph LR
        COMP2011[Programming with C++] --> COMP2012[Object-Oriented Programming and Data Structures]
        COMP2011 --> COMP2611[Computer Organization]
        COMP2711[Discrete Mathematical Tools for Computer Science]
        COMP2012 --> COMP3021[Java Programming] & COMP3031[Princinples of Programming Languages] & COMP3111[Software Engineering]
        COMP2011 --> COMP3211[Fundamentals of Artificial Intelligence]
        COMP2011 --> COMP3311[Database Management Systems]
        COMP2611 & COMP2011 --> COMP3511[Operation Systems]
        COMP2012 --> COMP3632[Principles of Cybersecurity]
        COMP2011 & COMP2711 --> COMP3711[Design and Analysis of Algorithms]
        COMP3711 & MATH2121[Linear Algebra] --> COMP3721[Theory of Computation]
        COMP2012 --> COMP4021[Internet Computing]
        COMP3111 --> COMP4111[Software Engineering Practices]
        COMP2012 & MATH2411[Applied Statistics] --> COMP4211[Machine Learning]
        MATH2411 --> COMP4221[Introduction to Natural Language Processing]
        COMP2011 & COMP2711 & MATH2121 --> COMP4222[Machine Learning with Structured Data]
        COMP2011 --> COMP4321[Search Engines for Web and Enterprise Data]
        MATH2411 --> COMP4331[Data Mining]
        COMP4221 --> COMP4332[Big Data Mining and Management]
        COMP3711 --> COMP4411[Computer Graphics]
        COMP2011 & MATH2121 --> COMP4421[Image Processing]
        COMP2012 --> COMP4431[Multimedia Computing]
        COMP2011 --> COMP4441[Computer Music]
        COMP4411 --- COMP4451[Game Programming]
        COMP2011 --> COMP4461[Human-Computer Interaction]
        COMP2011 --> COMP4462[Data Visualization]
        COMP2011 & MATH2121 --> COMP4471[Deep Learning in Computer Vision]
        COMP3511 --> COMP4511[System and Kernel Programming in Linux]
        COMP4621[Computer Communication Networks I, II] --- COMP4511
        COMP3511 --> COMP4521[Mobile Application Development]
        COMP2611 --> COMP4611[Design and Analysis of Computer Architectures]
        COMP3511 --> COMP4621
        COMP3711 --> COMP4631[Computer and Communication Security]
        COMP2012 --> COMP4632[Practicing Cybersecurity: Attacks and Counter-measures]
        COMP3511 --- COMP4632
        COMP2011 & MATH2411 --> COMP4641[Social Information Network Analysis and Engineering]
        COMP2011 --> COMP4651[Cloud Computing and Big Data Systems]
        COMP3511 & COMP3711 --> COMP4901D[Heterogeneous Parallel Programming]
        COMP2012 & MATH2411 --> COMP4901I[Building Interactive Intelligent Systems]
        COMP3711 & MATH2121 --> COMP4901L[Foundations of Computer Vision]
        COMP4901M[Artificial Intelligence Ethics]
        COMP2011 --> COMP4901Q[High Performance Computing]
        MATH2121 & MATH2411 & COMP3711 --> COMP4901R[Algorithmic Game Theory]
        COMP4901S[IoT and Mobile Sensing]
        COMP2012 --> COMP4901U[Computer Language Processing]
        COMP3311 --> COMP4901V[Database Technologies for Scalable Data Science]
        COMP2012 & COMP2711 --> COMP4901W[Introduction to Blockchain, Cryptocurrencies, and Smart Contracts]
        COMP2011 --> COMP4911[IT Entrepreneurship]
        MATH2421[Probability]
        subgraph Advanced Study
        COMP5111[Fundamentals of Software Testing and Analysis]
        COMP5112[Parallel Programming]
        COMP5211[Advanced Artificial Intelligence]
        COMP5212[Advanced Machine Learning]
        COMP5213[Introducion to Bayesian Networks]
        COMP5214[Advanced Deep Learning Architectures]
        COMP5211[Natural Language Processing]
        COMP5222[Statistical Learning Models for Text and Graph Data]
        COMP5223[Perception and Information Processing for Robotics]
        COMP5311[Database Architecture and Implementation]
        COMP5331[Knowledge Discovery in Databases]
        COMP5411[Advanced Computer Graphics]
        COMP5421[Computer Vision]
        COMP5622[Advanced Computer Communications and Networking]
        COMP5631[Cryptography and Security]
        COMP5711[Introduction to Advanced Algorithmic Techniques]
        COMP5712[Introduction to Combinatorial Optimization]
        COMP5713[Computational Geometry]
        COMP6311E[Blockchain and Cryptocurrency Technologies]
        COMP6211E[Optimization for Machine Learning]
        COMP6211F[Mathematical Analysis of Machine Learning Algorithms]
        COMP6211G[Federated Learning]
        COMP6211H[Deep Learning in Medical Image Analysis]
        COMP6411B[Advanced Topics in 2D and 3D Deep Visual Scene Understanding]        
        COMP6613E[Theory of Types and Programming Languages]
        end
        COMP3511 & COMP3711 --> COMP5112
        COMP2012 & MATH2121 & MATH2421 --> COMP5212
        MATH2411 & MATH2421 --> COMP5213
        COMP3211 --> COMP5211
        COMP3511 --> COMP5311
        COMP3311 --> COMP5331
        COMP3711 & MATH2121 & MATH2023[Multivariable Calculus] --> COMP5411
        COMP3211 & MATH2121 --> COMP5421
        COMP4621 --> COMP5622
        COMP4621 --> COMP5631
        COMP3711 & COMP3721 --> COMP5711
        COMP3711 & MATH2121 --> COMP5712
        COMP3711 --> COMP5713
        MATH2411 --> MATH4432[Statistical Machine Learning]
        MATH2121 & MATH2411 & MATH2421 & MATH4432 --> COMP6211F
        COMP2711 --> COMP6613E
        COMP4421 & COMP4211 --> COMP6211H
        COMP4471 --> COMP6411B
        COMP4211 & MATH2121 & MATH2023 & MATH2421 --> COMP6211E
        COMP2711 & COMP4631 --> COMP6311E
        







</div>

---

# Undergraduate Computer Science

## Programming with C++
<details>
<summary>Study material</summary>
<div markdown="1">
- #Big C++: Late Objects# by Cay Horstmann
</div>
</details>
>This course covers programming and data structures using C++. In addition to basic programming concepts such as variables and control statements, students will learn about arrays, pointers, dynamic data allocation, linked lists, stacks, queues, binary trees, recursion, and the basics of object oriented programming.

## Object-Oriented Programming and Data Structures
>To learn the fundamental concepts and techniques behind object-oriented programming. They include: abstract data types; creation, initialization, and destruction of objects; class hierarchies; polymorphism, inheritance and dynamic binding; generic programming using templates. To learn the object-oriented view of data structures: linked lists, stacks, queues, binary trees, and algorithms such as searching and hashing.

## Computer Organization
>Inner workings of modern digital computer systems and tradeoffs at the hardware-software interface. Topics include: instructions set design, memory systems, input-output systems, interrupts and exceptions, pipelining, performance and cost analysis, assembly language programming, and a survey of advanced architectures.

## Discrete Mathematical Tools for Computer Science
>Basic concepts in discrete mathematics needed for the study of computer science: enumeration techniques, basic number theory, logic and proofs, recursion and recurrences, probability theory and graph theory. The approach of this course is specifically computer science application oriented.

## Java Programming
>Introduction to Java programming. Fundamentals include language syntax, object-oriented programming, inheritance, polymorphism, exception handling, multithreading and lambdas. Standard libraries for input/output, graphics programming, built-in data structures. Programming for events, generics and higher-order functions.

## Principles of Programming Languages
>Comparative studies of programming languages, programming language concepts and constructs. Non-imperative programming paradigms: object-oriented, functional, logic, concurrent programming. Basic concepts of program translation and interpretation. Storage allocation and run-time organization.

## Software Engineering
>Methods and tools for planning, designing, implementing, validating, and maintaining large software systems. Project work to build a software system as a team, using appropriate software engineering tools and techniques.

## Fundamentals of Artificial Intelligence
>Foundations underlying design of intelligent systems. Relations between logical, statistical, cognitive, biological paradigms; basic techniques for heuristic search, theorem proving, knowledge representation, adaptation; applications in vision, language, planning, expert systems.

## Database Management Systems
>Principles of database systems; conceptual modeling and data models; logical and physical database design; query languages and query processing; database services including concurrency, crash recovery, security and integrity. Hands-on DBMS experience.

## Operating Systems
>Principles, purpose and structure of operating systems; processes, threads, and multi-threaded programming; CPU scheduling; synchronization, mutual exclusion; memory management and virtual memory; device management; file systems, security and protection.

## Principles of Cybersecurity
>This course is an introduction to the principles of cybersecurity. Cybersecurity, also called computer security or IT security, refers to the study of techniques to protect computing systems from attacks that threaten data confidentiality, system integrity and availability. By modeling, analyzing, and evaluating the security of computer systems, students will learn to find weaknesses in software, hardware, networks, data storage systems, mobile applications, and the Internet, and identify current security practices and defenses to protect these systems.

## Design and Analysis of Algorithms
>Techniques for designing algorithms, proving their correctness, and analyzing their running times. Topics covered include: sorting, selection, heaps, balanced search trees, divide-and-conquer, greedy algorithms, dynamic programming, and graph algorithms.

## Theory of Computation
>This course is an introduction to the foundation of computation. Topics covered include set theory and countability, formal languages, finite automata and regular languages, pushdown automata and context-free languages, Turing machines, undecidability, P and NP, NP completeness.

## Internet Computing
>Technologies and standards for World Wide Web (WWW), user interfaces and Browsers, authoring tools, Internet protocols, Internet servers, database connectivity, Robots, Search engines, server-side programming, client-side programming, security and privacy, recent advances.

## Software Engineering Practices
>This course provides students with the exposure of effective real-world software engineering practices and the underlying concepts via working around a realistic modern software system and applying popular tools and practices in industry. Students will gain experience in collaborative software development as well as the skills required to succeed as software professional. Topics of the course cover advanced software engineering concepts, project setup, code management, testing, defect analysis, quality metrics, and issue management. For students of the Department of Computer Science and Engineering only.

## Machine Learning
>Fundamentals of machine learning. Concept learning. Evaluating hypotheses. Supervised learning, unsupervised learning and reinforcement learning. Bayesian learning. Ensemble Methods. Deep learning.

## Introduction to Natural Language Processing
>Human language technology for text and spoken language. Machine learning, syntactic parsing, semantic interpretation, and context-based approaches to machine translation, text mining, and web search.

## Machine Learning with Structured Data
>This course provides an introduction to statistical machine learning algorithms for structured data such as text sequences, taxonomy trees, relational databases (such as knowledge bases), and graphs (including graph databases such as biomedical graphs and large heterogeneous information networks such as knowledge graphs), and using programming tools such as Python to implement them for real problems. It will use some of the following practical problems such as text and graph classification, statistical relational learning, information extraction, sequence modeling, graph modeling, protein 3D structure prediction, QA system, etc. as illustrations to demonstrate the power of the statistical learning algorithms.

## Search Engines for Web and Enterprise Data
>Text retrieval models, vector space model, document ranking, performance evaluation; indexing, pattern matching, relevance feedback, clustering; web search engines, authority-based ranking; enterprise data management, content creation, meta data, taxonomy, ontology; semantic web, digital libraries and knowledge management applications.

## Data Mining
>This course will provide an introduction to concepts and techniques in the field of data mining. Materials include an introduction to data warehousing and OLAP, data preprocessing and the techniques used to explore the large quantities of data for the discovery of predictive models and knowledge. The course will include techniques such as nearest neighbor, decision tress, neural networks, Bayesian networks and Naive Bayes, rule-based methods, association analysis and clustering, as well as social networks and data mining applications in business and finance applications, and other emerging data mining subareas. Students learn the materials by attending lectures and implementing and applying different data analysis and mining techniques to large datasets throughout the semester.

## Big Data Mining and Management
>This course will expose students to new and practical issues of real world mining and managing big data. Data mining and management is to effectively support storage, retrieval, and extracting implicit, previously unknown, and potentially useful knowledge from data. This course will place emphasis on two parts. The first part is big data issues such as mining and managing on distributed data, sampling on big data and using some cloud computing techniques on big data. The second part is applications of the techniques learnt on areas such as business intelligence, science and engineering, which aims to uncover facts and patterns in large volumes of data for decision support. This course builds on basic knowledge gained in the introductory data-mining course, and explores how to more effectively mine and manage large volumes of real-world data and to tap into large quantities of data. Working on real world data sets, students will experience all steps of a data-mining and management project, beginning with problem definition and data selection, and continuing through data management, data exploration, data transformation, sampling, portioning, modeling, and assessment.

## Computer Graphics
>Display technologies; scan conversion; clipping; affine transformations; homogeneous coordinates and projection; viewing transformations; hidden surface removal; reflectance and shading models; ray tracing; spline curves and surfaces; hierarchical modeling; texture mapping; color models.

## Image Processing
>Introduction to image processing. Topics include image processing and analysis in spatial and frequency domains, image restoration and compression, image segmentation and registration, morphological image processing, representation and description, object recognition, related application areas and some other closely related topics. Some sophisticated image processing and analysis tools and state-of-the-art methods may also be introduced subject to the availability of time.

## Multimedia Computing
>Color theory; digital audio, image and video fundamentals, representation, and processing; digital multimedia applications and programming.

## Computer Music
>This experiential project course will provide hands-on experiences in creating music and soundtracks with a wide range of emotional characteristics for a variety of situations in computer games and videos. The course is structured as if at an LA film school for sound designers, and contrasting in style and content from other UST courses, where the primary focus includes emotional not just technical control. This course will provide a creative outlet for applying problem-solving in a deep and engaging way to music. Whether students have music background or not, this course will provide them a chance to explore music almost like a composer. Students will share their musical creations and learn from one another, and create music that modulates the moods of listeners.

## Game Programming
>Computer game development touches on many facets of computer science, including computer graphics, artificial intelligence, algorithms, networking, human-computer interaction, music, and sound. This course will cover all of these aspects, with special emphasis on real-time graphics rendering. Students will get hands-on experience on how to design and implement real-world computer games, which will help improve their skills in programming, teamwork, management, and communication.

## Human-Computer Interaction
>This course is a broad introduction to Human-Computer Interaction (HCI), with an emphasis on techniques, models, theories, and applications for designing, prototyping, and evaluating current and future interactive systems for human use. HCI is an interesting and important area of study, providing the human perspective to computing. Besides technology and innovation, it also touches on issues like ethics and social responsibilities related to technologies in the real world. Selected topics include multimodal interaction design, usability evaluation, computer-supported cooperative work, assistive technologies, social computing, crowd computing, ubiquitous/mobile computing, virtual/augmented reality and gaming, agents and robots, and HCI applications in various domains such as education, health, urban sustainability, scientific discoveries, etc.

## Data Visualization
>This course will introduce visualization techniques for data from everyday life, social media, business, scientific computing, medical imaging, etc. The topics include human visual system and perception, visual design principles, open- source visualization tools and systems, visualization techniques for CT/MRI data, computational fluid dynamics, graphs and networks, time-series data, text and documents, Twitter data, and spatio-temporal data. The labs and the course project will give students hands-on experience to turn their data into beautiful visualizations.

## Deep Learning in Computer Vision
>Deep learning has significantly advanced the performance of computer vision system from object recognition to image processing. This course covers the basics and various applications of deep learning in computer vision. Students will study the details of convolutional neural networks as well as recurrent neural networks and train deep networks with end-to-end optimization, and learn deep learning based approaches for both high-level and low-level computer vision tasks such as image recognition and image enhancement. Through programming projects, students will implement, train, and test deep neural networks on cutting-edge computer vision research. Students would be required to study or do research in a final course project related to deep learning and computer vision and present their work by the end of the course.

## System and Kernel Programming in Linux
>This course is designed to equip students, who have a particular interest in becoming practitioners, with substantial hands-on experience in solving concrete problems in a computer operating system, via programming, in a laboratory intensive course. Students will notably experiment with many topics in the areas of operating systems and network protocols, such as: boot loaders, shell, process management, system calls, process scheduler, file system, virtual memory, network protocols and packet filtering, system modules and device drivers. For students of the Department of Computer Science and Engineering only.

## Mobile Application Development
>Principles of application development for mobile and embedded devices. Mobile software development environments and software architectures. Features of typical mobile platforms: user-interface and user-experience design, multimedia, 2D and 3D graphics and data storage support, networking, location and mapping services. Design patterns and application frameworks. Mobile back-end support. Web applications. Students need to design and implement a full-fledged mobile application.

## Design and Analysis of Computer Architectures
>Analysis, synthesis and evaluation of different computer architectures. Emphasis on computer design with respect to price/performance and its relation to architectural choices such as pipelining, memory hierarchy, input/output, instruction set design, vector processing, and multiprocessing.

## Computer Communication Networks I, II
>Principles of computer network architectures and communication protocols; the OSI reference model; switching and multiplexing techniques; data link, network, transport and application layers; LAN and medium access protocols; network programming.

>Principles, design and implementation of computer communication networks; network architecture and protocols, OSI reference model and TCP/IP networking architecture; Internet applications and requirements; transport protocols, TCP and UDP; network layer protocols, IP, routing, multicasting and broadcasting; local area networks; data link and physical layer issues; TCP congestion control, quality of service, emerging trends in networking.

## Computer and Communication Security
>Cryptosystems, symmetric-key and public-key cryptography, cryptanalysis, authentication, message digests, digital signatures, and random number generation. Access controls and firewalls. Applications such as certificate authorities, electronic commerce, smartcards, and digital cash.

## Practicing Cybersecurity: Attacks and Counter-measures
>This course equips students with cybersecurity knowledge and current IT practices on security risk management. Through hands-on laboratory sessions, students will understand existing IT security issues, learn how to assess IT security risks, and conduct experiments on ethical hacking. They will practice system attack and defense strategies using security tools, so as to gain practical experience to become a cybersecurity professional. The course covers current security trends, industrial practices on IT security, design requirements for secure web and mobile applications, security assessment, risk analysis and risk management. Knowledge in web programming and database administration is not essential but a plus.

## Social Information Network Analysis and Engineering
>This course is an introduction to social information network analysis and engineering. Students will learn both mathematical and programming knowledge for analyzing the structures and dynamics of typical social information networks (e.g. Facebook, Twitter, and MSN). They will also learn how social metrics can be used to improve computer system design as people are the networks. It will cover topics such as small world phenomenon; contagion, tipping and influence in networks; models of network formation and evolution; the web graph and PageRank; social graphs and community detection; measuring centrality; greedy routing and navigations in networks; introduction to game theory and strategic behavior; social engineering; and principles of computer system design. Students who do not have the prerequisites but with equivalent background may seek approval from the instructor for enrollment in the course.

## Cloud Computing and Big Data Systems
>Big data systems, including Cloud Computing and parallel data processing frameworks, emerge as enabling technologies in managing and mining the massive amount of data across hundreds or even thousands of commodity servers in datacenters. This course exposes students to both the theory and hands-on experience of this new technology. The course will cover the following topics. (1) Basic concepts of Cloud Computing and production Cloud services; (2) MapReduce - the de facto datacenter-scale programming abstraction - and its open source implementation of Hadoop. (3) Apache Spark - a new generation parallel processing framework - and its infrastructure, programming model, cluster deployment, tuning and debugging, as well as a number of specialized data processing systems built on top of Spark. By walking through a number of hands-on labs and assignments, students are expected to gain first-hand experience programming on real world clusters in production datacenters.

## Heterogeneous Parallel Programming
>This course introduces the concepts, languages, techniques, and patterns for programming heterogeneous, massively parallel processors such as the GPU and multicore CPUs. Specifically, we will cover heterogeneous computing architectures, data-parallel programming models, techniques for memory bandwidth management, and parallel algorithm patterns. We will use CUDA C as the main programming language.

## Building Interactive Intelligent Systems
>This course covers the basic theories and applications of language-based and interactive intelligent system using deep learning. Topics include distributional semantics with word embeddings, text classification, emotion recognition, sentiment analysis from text and speech, and language modeling, with neural networks and back-propagation, convolutional neural networks, and recurrent neural networks. We will also cover multi-linguality and multi-modality, end-to-end chatbots, and task-oriented dialogue systems. Students will learn about various natural language processing (NLP) tasks related to building interactive intelligent systems, how to design and build a deep learning model using PyTorch and Python, and the basics of software engineering. At the end of the course, students will work alone or in pairs to implement a deep learning model for various NLP research tasks, and describe their methods and results in a conference paper format. Successful groups will be able to submit their papers to an international conference.

## Foundations of Computer Vision
>This course provides a comprehensive introduction to computer vision. Major topics include image processing, detection and recognition, geometry-based and physics-based vision and video analysis. Instructor's approval is required for enrollment in the course.

## Artificial Intelligence Ethics
>This course critically surveys the fast moving, urgent, emerging area of AI ethics. AI is explosively disrupting every sphere of our work and lives. Cambridge Analytica and fake news bots. AI driven social media displacing traditional journalism. Drone warfare. Elimination of traditional jobs. Privacy-violating advertising. Biased AI decision/recognition algorithms. Deepfakes. Autonomous vehicles. Automated hedge fund trading. No area remains untouched. Policy think tanks, governments, and tech companies around the world have started paying serious attention to AI ethics. How will human civilization survive the rise of AI? What are the new rules? What are the ethical frameworks needed to avoid extinction? What are engineers’ and entrepreneurs’ ethical responsibilities?

## High Performance Computing
>High performance computing (HPC) plays an important role in solving many science and engineering problems, e.g., understanding the universe through simulation, simulating the climate change, training large-scale artificial intelligence models, etc. The development of computing power (from our desktop computers to high performance supercomputers) is fast, so it is very useful for students to understand and master how to use or develop high performance systems to solve real-world challenging problems. This course will begin with an introduction to HPC, which targets at making students understand what HPC is. Next, students will learn the fundamental knowledge of hardware architecture (e.g., parallel processors, distributed memory clusters, etc.) that supports HPC. Then the parallel programming classes (e.g., OpenMP, CUDA, MPI, etc.) that make use of parallel computers to solve science and engineering problems will be offered. Finally, the students will be expected to use or develop high performance systems for practical applications.

## Algorithmic Game Theory
>This course is an introduction to modern algorithmic game theory. Topics covered include combinatorial games, zero and general sum games, Nash Equilibria and the Price of Anarchy as well as an introduction to Auction Theory and Mechanism design.

## IoT and Mobile Sensing
>The objective of this course is to introduce the spectrum of research on the Internet of Things (IoT) and mobile sensing. The lectures cover a range of techniques in sensing, computing, communication, and wireless networking and connect them to various applications in analytics, localization, cyber-physical systems, mobile health, security, and wearables. This course is designed with multidisciplinary students in mind. The course is designed to be self-contained. It will cover introductory materials on mathematics and signal processing basics. Familiarity with the undergraduate level calculus, probability, linear algebra, and programming is preferred. For COMP, COSC, CPEG and ELEC students in their second, third or fourth year of study only.

## Computer Language Processing
>Computer languages are now everywhere. Thus, basic computer language processing skills are essential to any self-respecting software engineer. From parsing ad-hoc configuration file formats, to validating complex specification languages, to generating efficient code solving data-intensive problems at scale, many important problems of today and tomorrow fall within this general domain. In this context, the usefulness of compiler theory and practice goes much beyond understanding the technology underlying your grandpa's old C compilers – our software-driven world is full of domain-specific languages that need correct and efficient implementations, and emergent areas like machine learning are more than ever in need of innovations from the fields of compilation and optimization. In this course, you will learn the essentials of computer language processing, including: parsing, analyzing, transforming, and compiling programs. You will learn to design and implement your own programming language and extend it with features of your choice in a small team project.

## Database Technologies for Scalable Data Science
>Data science is enabled by very large volume of fast changing data with complex and dynamic structures. Data management is at the core of advanced data analytics. In this course, we will first discuss the fundamental concepts and their limitations of relational database systems. The main topics to be studied in this course include modern data management and processing technologies for massively distributed environment, for unstructured and semi-structure data, and for graph data. This course also covers emerging topics such as database and AI, database systems with new hardware platforms, and cloud databases.

## Introduction to Blockchain, Cryptocurrencies and Smart Contracts
>This course provides a holistic introduction to the world of Blockchain Protocols and Smart Contracts. You will learn how cryptocurrencies such as Bitcoin and Ethereum work, why they are secure, and how you can use them to develop smart contracts. You will also learn to detect and avoid common security vulnerabilities in smart contracts. This is a very hands-on course with lots of extra-credit homeworks and mini-projects and no final exam. The course covers the following topics: basics of cryptography, the double-spending problem in decentralized currencies, Proof-of-work and its alternatives, programmable blockchains and smart contracts, auctions and escrows, common smart contract vulnerabilities, and tools for verifying the correctness of a smart contract.

## IT Entrepreneurship
>Basic elements of starting a new business in information technology; exploiting an "unfair" advantage; preparing a business plan; arranging financial support; accounting and legal requirements; exit strategy.

# Undergraduate Mathematics
## Multivariable Calculus
>Sequences, series, gradients, chain rule. Extrema, Lagrange multipliers, line integrals, multiple integrals. Green's theorem, Stoke's theorem, divergence theorem, change of variables.

## Linear Algebra
>Vector space, matrices and system of linear equations, linear mappings and matrix forms, inner product, orthogonality, eigenvalues and eigenvectors, symmetric matrix.

## Applied Statistics
>A systematic introduction to statistical inference, including the necessary probabilistic background, point and interval estimation, hypothesis testing.

## Probability
>Sample spaces, conditional probability, random variables, independence, discrete and continuous distributions, expectation, correlation, moment generating function, distributions of function of random variables, law of large numbers and limit theorems.

## Statistical Machine Learning
>This course provides students with an extensive exposure to the elements of statistical machine learning in supervised and unsupervised learning with real world datasets. Topics include regression, classification, resampling methods, model assessment, model selection, regularization, nonparametric models, boosting, ensemble methods, random forests, kernel methods, support vector machines, neural networks, and some standard techniques in unsupervised learning such as clustering and dimensionally reduction. Lab sessions on using R or Python in data analysis with machine learning methods will be conducted in class. Scientific reports and/or poster presentations are required for project evaluations.

# Postgraduate Computer Science
## Fundamentals of Software Testing and Analysis
>The goal of this course is to introduce how various analysis techniques can be used to manage the quality of a software application. Students will acquire fundamental knowledge of program abstraction, features, verification, testing, refactoring, concurrency, reliability, aspect orientation, and fault analysis. The course will also discuss how to carry out the empirical experimentation for program analysis. Wherever applicable, concepts will be complemented by tools developed in academia and industry. This enables students to understand the maturity and limitations of various analysis techniques.

## Parallel Programming
>Introduction to parallel computer architectures; principles of parallel algorithm design; shared-memory programming models; message passing programming models used for cluster computing; data-parallel programming models for GPUs; case studies of parallel algorithms, systems, and applications; hands-on experience with writing parallel programs for tasks of interest.

## Advanced Artificial Intelligence
>This advanced AI course will cover advanced concepts and techniques in AI. The major topics will be: problem solving, knowledge and reasoning, planning, uncertain knowledge and reasoning, learning, and robotics.

## Advanced Machine Learning
>Introduction to major learning paradigms and techniques, basic applied statistics and information theory, decision trees, neural networks, Bayesian classification, kernel methods, clustering, density estimation, feature selection and extraction, hidden Markov models, reinforcement learning, case-based learning, model selection and various applications.

## Introduction to Bayesian Networks
>Bayesian networks and probabilistic modeling of complex domains; conditional independence and graph separation; variable elimination, clique tree propagation, and other inference algorithms; parameter learning; structure learning; latent structure models; recent developments.

## Advanced Deep Learning Architectures
>This course focuses on advanced deep learning architectures and their applications in various areas. Specifically, the topics include various deep neural network architectures with applications in computer vision, signal processing, graph analysis, and natural language processing. Different state-of-the-art neural network models will be introduced, including graph neural networks, normalizing flows, point cloud models, sparse convolutions,and neural architecture search. The students have the opportunities to implement deep learning models for some AI-related tasks such as visual perception, image processing and generation, graph processing, speech enhancement, sentiment classification, and novel view synthesis.

## Natural Language Processing
>Techniques for parsing, interpretation, context modeling, plan recognition, generation. Emphasis on statistical approaches, neuropsychological and linguistic constraints, large text corpora. Applications include machine translation, dialogue systems, cognitive modeling, and knowledge acquisition.

## Statistical Learning Models for Text and Graph Data
>This course will introduce a number of important statistical methods and modeling principles for analyzing large-scale data sets, with a focus on complex data structures such as text and graph data. Topics covered include sequential models, structure prediction models, deep learning attention models, reinforcement learning models etc., as well as open research problems in this area.

## Perception and Information Processing for Robotics
>This course introduces the essential theoretical frameworks, methods, concepts, tools and techniques used to enable robotic perception and behavior, with particular emphasis on applications in autonomous mobile robots. The course starts from Bayesian programming and probabilistic methods, and then moves on to cover generic machine learning, especially deep learning. For each knowledge point, practical examples will be discussed with guidance to selection of methods. It also covers reinforcement learning with the application in complex system control. Important libraries for hands-on experiments for mobile robotic systems will be introduced. The students will have the opportunity to test their algorithms and implementations on real platforms.

## Database Architecture and Implementation
>Introduction to the relational model and SQL. System architectures and implementation techniques of database management systems: disk and memory management, access methods, implementation of relational operators, query processing and optimization, transaction management and recovery. Hands on experience with building the components of a small DBMS.

## Knowledge Discovery in Databases
>An introduction to knowledge discovery in databases. Different discovery and learning techniques are presented and compared. Automatic generation of query language expressions is discussed in depth. Potential applications are shown.

## Advanced Computer Graphics
>The first part of this course covers an introduction to mathematical tools and computational techniques for image synthesis and manipulation of 3D models. The second part covers more advanced topics which may include digital geometry processing, image processing, visualization, GPU computing, numerical optimization methods.

## Computer Vision
>Introduction to techniques for automatically describing visual data and tools for image analysis; perception of spatial organization; models of general purpose vision systems; computational and psychological models of perception.

## Advanced Computer Communications and Networking
>Advanced principles in computer and communication networking: Internet multicast, overlay and peer-to-peer networks; wireless and mobile computing, multimedia networking, network security, selected topics of current interests: wireless protocols, wireless security, sensor networks, cloud computing, data centers, software-defined networks, network implementation, etc.

## Cryptography and Security
>Classical encryption techniques, block and stream ciphers, public-key cryptography, authentication, nonrepudiation, key management, digital signatures, public key infrastructure, cryptographic protocol, secret sharing, electronic mail security, IP security, Web security, Firewalls, Intrusion detection.

## Introduction to Advanced Algorithmic Techniques
>This is an introductory graduate course in algorithmic techniques. Topics include: advanced data structures; graph algorithms; amortization; approximation algorithms; on-line algorithms; randomized and probabilistic analysis.

## Introduction to Combinatorial Optimization
>An introduction to the basic tools of combinatorial optimization, including network flow and the max-flow min-cut theorem, linear programming, matching, spanning trees and matroids, dynamic programming, algorithms and data structures, graph algorithms.

## Computational Geometry
>An introductory course in Computational Geometry. Algorithms for manipulating geometric objects. Topics include Convex Hulls, Voronoi Diagrams, Point Location, Triangulations, Randomized Algorithms, Point-Line Duality.

## Optimization for Machine Learning
>This course covers modern optimization methods for machine learning applications. We will discuss both theory and implementation of common optimization algorithms in the context of machine learning applications. The topics covered include convex optimization, stochastic optimization, nonconvex optimization, and distributed optimization. Knowledge with calculus, linear algebra, and probability, basic machine learning are required.

## Mathematical Analysis of Machine Learning Algorithms
>This is an advanced graduate course for students who are already familiar with basic machine learning algorithms such as support vector machines, decision trees, boosting, neural networks etc, and has learned the basic mathematical tools such as calculus, linear algebra, and probability. This is mainly a mathematical class, and the goal is to introduce the basic techniques in the theoretical analysis of machine learning algorithms, with motivations and applications.

## Federated Learning
>This course introduces the basic concepts, frameworks, applications and open problems in the emerging field federated learning. It includes discussions on important topics such as privacy, communication efficiency and incentives.

## Deep Learning in Medical Image Analysis
>Nowadays medical image analysis is rapidly growing and plays an indispensable role in healthcare. Recent advances of deep learning techniques have made significant breakthroughs in medical image analysis applications. This course will cover fundamental knowledge of medical imaging and various medical image analysis tasks, including computer-aided detection, segmentation, diagnosis and prognosis. Deep learning methods for solving these tasks will be introduced and state-of-the-art methods will be discussed. The remaining significant challenges and limitations will also be presented, including limited amount of labeled data, deep learning with interpretation and generalization issues, etc. This course will equip students with practical knowledge of medical imaging and analysis with deep learning techniques. Instructor’s approval is required.

## Blockchain and Cryptocurrency Technologies
>The course will provide an introduction to blockchains, a tool that promises to revolutionize monetary transactions. We will start by analyzing the Bitcoin decentralized cryptocurrency that is the most popular existing blockchain application. We will examine in detail how Bitcoin transactions are created, how Bitcoins are mined, and what are the security guarantees of the protocol. Then we will look into other applications of blockchains, including smart contract execution, distributed storage, and alternative cryptocurrencies, by reviewing recent research literature.

## Advanced Topics in 2D and 3D Deep Visual Scene Understanding
>Visual scene understanding is an important and fundamental field for advanced application scenarios such as autonomous driving and robotics. This course majorly focuses on delivering deep learning-based visual scene understanding techniques in both 2D and 3D perspectives. In the 2D part, it introduces topics including image and scene classification, semantic segmentation, and object detection. In the 3D part, it shows how 3D scene understanding can be performed through learning from 2D inputs, involving topics such as scene depth estimation, camera pose prediction, 3D scene reconstruction, and visual SLAM. Several representative deep scene understanding architectures and frameworks in supervised or self-supervised settings together with the 2D/3D tasks are also presented in the course.

## Theory of Types and Programming Languages
>This course studies types and programming languages from a type-theoretic perspective. Starting from lambda calculus, the foundation of functional programming languages, we see how to design gradually more advanced type systems following the motto “Well-typed programs do not go wrong”, meaning that types should guard us, at compilation time, from wide classes of runtime errors. Taking this principle to the extreme, we see how dependent type systems let us prove nontrivial properties of our programs, and how they relate to mathematical logic in a fundamental way. The knowledge acquired in this course has many practical applications in software engineering and computer science. It will sharpen the student’s understanding of static types in modern programming languages, as well as their ability to construct correct and reliable programs. Topics covered include lambda calculus, operational semantics, type systems, programming language theory and metatheory.


#### Reference

- https://prog-crs.hkust.edu.hk/ugcourse
- https://prog-crs.hkust.edu.hk/pgcourse