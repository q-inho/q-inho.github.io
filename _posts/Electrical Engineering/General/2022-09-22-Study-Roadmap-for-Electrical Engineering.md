---
title:  "Study Roadmap for Electrical Engineering"
excerpt: "Bioelectronics, Electromagnetics, Embedded Systems, Integrated Circuits and Systems and others.."

categories:
  - elec-general
tags:
  - [Electrical Engineering]

toc: false
toc_sticky: false
 
date: 2022-09-22
last_modified_at: 2022-09-22
---

# My Roadmap for Electrical Engineering

<div class="mermaid"> 
      graph LR
        ELEC2100[Signals and Systems]
        MATH2023[Multivariable Calculus] --> ELEC2100
        ELEC2350[Introduction to Computer Organization and Design]
        ELEC2400[Electronic Circuits]
        ELEC2600[Probability and Random Processes in Engineering]
        ELEC2600 --- MATH2023
        ELEC2100 & ELEC2600 --> ELEC3100[Signal Processing and Communications]
        ELEC3120[Computer Communication Networks]
        MATH2121[Linear Algebra]
        ELEC2600 & MATH2121 --> ELEC3180[Data-Driven Portfolio Optimization]
        
        ELEC2100 & MATH2121 & MATH2352[Differential Equations] --> ELEC3200[System Modeling, Analysis and Control]
        ELEC3200 --> ELEC3210[Machine Learning and Information Processing for Robotics]
        ELEC2350 --> ELEC3300[Introduction to Embedded Systems]
        ELEC3310[Digital Fundamentals and System Design]
        ELEC2400 --> ELEC3400[Introeduction to Integrated Circuits and Systems]
        ELEC3450[Introduction to Smart Electric Power Systems]
        ELEC2400 --> ELEC3500[Microelectronic devices and Technology]
        MATH2023 & MATH2352 --> ELEC3600[Electromagnetics: From Wireless to Photonic Applications]
        ELEC2100 --> ELEC4110[Digital Communications and Wireless Systems]
        MATH2121 --> ELEC4130[Machine Learning on Images]
        ELEC2100 --> ELEC4150[Information Theory and Error-Correcting Codes]
        ELEC3200 --> ELEC4210[Control System Design]
        ELEC3200 --> ELEC4220[Introduction to Robotics: From Mobile Robots to Manipulators]
        COMP2011[Programming with C++]
        COMP2011 --> COMP2012[Object-Oriented Programming and Data Structures]
        COMP2012 & ELEC2600 --> ELEC4230[Deep Learning for Natural Language Processing]
        COMP2012 & MATH2121 --> ELEC4240[Deep Learning in Computer Vision]
        ELEC3200 --> ELEC4250[Robotic Manipulation and Mobility]
        ELEC2350 --> ELEC4310[Embedded System Design]
        ELEC2350 --> ELEC4320[FPGA-based Design: From Theory to Practice]
        ELEC2350 --> ELEC4330[Mobile Embedded Systems: Hardware Platform, Software Development, and Applications]
        ELEC3310 --> ELEC4410[CMOS VLSI Design]
        ELEC3400 --> ELEC4420[Analogue Integrated Circuits Design and Analysis]
        ELEC3400 --> ELEC4430[Integrated Power Electronics]
        ELEC3500 --> ELEC4510[Semiconductor Materials and Devices]
        ELEC3500 --> ELEC4520[Integrated Circuit Fabrication Technology]
        ELEC3500 --> ELEC4530[Fundamentals of Photovoltaic and Renewable Energy]
        ELEC2400 --> ELEC4610[Engineering Optics]
        ELEC3600 --> ELEC4620[Photonics and Optical Communications]
        ELEC3600 --> ELEC4630[Radio Frequency Engineering]
        ELEC2400 --> ELEC4810[Introduction to Bionsensors and Bioinstrumentation]
        ELEC2100 & MATH2121 & MATH2023 --> ELEC4820[Medical Imaging]
        MATH2121 & ELEC2600 --> ELEC4830[Statistical Signal Analysis and Applications in Neural Engineering]
        
        subgraph Advanced Study
        ELEC5010[Introduction to the Design & Implementation of Micro-Systems]
        ELEC5040[Advanced Analog IC Analysis and Design]
        ELEC5050[Advanced CMOS Devices]
        ELEC5070[Microelectronics Fabrication Technology]
        ELEC5090[Advanced Photonics Technologies]
        ELEC5110[Nanoelectronic Materials for Energy Technologies]
        ELEC5120[Semiconductor Power and Energy Conversion Technologies]
        ELEC5140[Advanced Computer Architecture]
        ELEC5160[Digital VLSI System Design and Design Automation]
        ELEC5180[RF/Microwave Circuit Design and Measurement]
        ELEC5190[Solid State and Semiconductor Electronics]
        ELEC5210[Advanced Topics in Nanoelectronics]
        ELEC5230[Novel Liquid Crystal Devices for Photonics and Displays]
        ELEC5240[Advanced Display Technologies]
        ELEC5280[High Frequency Circuit Design]
        ELEC5300[Stochastic Processes]
        ELEC5360[Principles of Digital Communications]
        ELEC5450[Random Matrix Theory and Applications]
        ELEC5460[Advanced Stochastic Optimization for Wireless Systems]
        ELEC5470[Convex Optimization]
        ELEC5510[Switch Mode Power Converters]
        ELEC5520[Power Management Integrated Circuit Design]
        ELEC5530[Mixed-Signal Integrated Bio-Sensory Circuit Design]
        ELEC5540[High Tech Innovation and Entreprenurship]
        ELEC5600[Linear-System Theory]
        ELEC5640[Robot Manipulation]
        ELEC5650[Introduction to Networked Sensing, Estimation and Control]
        ELEC5660[Introduction to Aerial Robotics]
        ELEC5670[Robot Perception and Learning]
        ELEC5680[Advanced Deep Learning Architectures]
        ELEC5810[Introduction to Bioinformatics Algorithms]
        ELEC5820[Microfluidics and Biosensors]
        end

        ELEC4420 & ELEC4510 --> ELEC5040
        ELEC3500 --> ELEC5050
        ELEC3500 --> ELEC5110
        
        ELEC2350 --> ELEC5140
        ELEC3310 --> ELEC5160
        ELEC3100 & ELEC3400 & ELEC3600 & ELEC4420 --> ELEC5180
       
        ELEC4510 --> ELEC5190
        ELEC4510 --> ELEC5210
        ELEC4610 --> ELEC5230
        MATH2023 & MATH2121 --> ELEC5240
        ELEC3100 & ELEC3400 & ELEC4630 & ELEC4110 --> ELEC5280
        ELEC2600 --> ELEC5300
        ELEC2600 --> ELEC5360
        ELEC2600 --> ELEC5450
        ELEC4110 --> ELEC5460
        ELEC3100 --> ELEC5470
        ELEC2100 & ELEC3400 --> ELEC5510
        ELEC4420 & ELEC4430 --> ELEC5520
        ELEC4420 --> ELEC5530
        ELEC2100 & MATH2352 & MATH2023 --> ELEC5600
        ELEC2600 & ELEC3200 --> ELEC5650
        MATH2121 & ELEC2600 & COMP2011 --> ELEC5660

        subgraph Robotics
        MECH2520[Design and Manufacturing I]
        COMP4211[Machine Learning]
        COMP4421[Image Processing]
        MECH3610[Control Principles]
        MECH3907[Mechatronic Design and Prototyping]
        MECH4710[Introduction to Robotics]
        MECH2020[Statistics and Dynamics]
        end

        COMP2012 & ELEC2600 --> COMP4211
        COMP2011 & MATH2121 --> COMP4421
        MECH2520 --> MECH3907
        MECH2020 --> MECH4710

        subgraph Sustainable Energy Engineering
        MECH2310[Thermodynamics]
        ENVR3110[Sustainable Development]
        ENVR3220[Energy Sources and Usage]
        MECH3300[Energy Conversion]
        MECH3630[Electrical Technology]
        ENVR3003[Green Buildings and Energy Efficiency]
        CHEM2111[Fundamentals of Organic Chemistry]
        CHEM4640[Chemistry for Advanced Solar Cell Technologies]
        end

        MECH2310 --> MECH3300
        CHEM2111 --> CHEM4640




</div>

---

# Undergraduate Elecetrical Engineering
## Signals and Systems
<details>
<summary>Study material</summary>
<div markdown="1">
- *Signals and Systems* by Alan Oppenheim
</div>
</details>
>This is an introductory course for signal and system analysis. The course covers signal analysis tools including continuous- and discrete-time Fourier series and Fourier transform, and Laplace Transform; interactions between signals and linear time invariant (LTI) systems, and differential and difference equations as LTI systems, sampling theorem; and application examples in communication and control systems. MATLAB introduced as an integral part of this course.

## Introduction to Computer Organization and Design
>This is an introductory course to computer hardware and software organization. The topics covered include computing systems, computing programing, hardware-software collaboration, computer arithmetic, computer hardware organizations and operations, parallel processing, memory technologies and organization, and technology trends.

## Electronic Circuits
>Fundamental electronic concepts for DC and AC circuits, KVL and KCL, Thevenin and Norton Theroems, linearity and superposition, nodal and mesh analyses, sinusoidal steady state and phasor, transient analysis, transfer functions and Bode plots, op-amps, diodes, MOS transistors and related circuits.

## Probability and Random Processes in Engineering
>An introduction to statistical inference and random processes in electrical engineering, including the necessary probabilistic background. Random variables, distribution and density functions, characteristic functions, conditional statistics, expectation, moments, stochastic processes.

## Signal Processing and Communications
>The course provides a comprehensive overview of signal processing and communications using quantitative modeling and analysis. Topics include: 7 layer communications model, discrete Fourier transform and z-transform, IIR and FIR filter design techniques and realizations, complexity and implementation considerations of FFT and FIR/IIR, source coding, digital modulation, PSD and spectrum, effects of noise to communication system designs, detection theory, matched filter, signal space and error analysis, channel models and channel coding. Application examples are provided to illustrate on how practical communication systems are designed using these quantitative tools. Design projects are set up so that the students can apply theory learnt in the class to physical problems. MATLAB CAD tools are being used as an integral part of this course.

## Computer Communication Networks
>Overview of computer networks: network architecture and switching techniques. Introduction to the Internet, network programming, and layer architecture. Application layer: HTTP, FTP, SMTP, and CDN. Transport layer: TCP and UDP. Network layer: IP routing, NAT, and DHCP. Data link layer and local area networks: MAC protocols, Ethernet, and hubs/bridges/switches.

## Data-Driven Portfolio Optimization
>Modern portfolio theory started with Harry Markowitz's 1952 seminal paper "Portfolio Selection." He put forth the idea that risk-adverse investors should optimize their portfolio based on a combination of two objectives: expected return and risk. Until today, that idea has remained central in portfolio optimization. However, the vanilla Markowitz portfolio formulation does not seem to behave as expected in practice and most practitioners tend to avoid it. During the past half century, researchers and practitioners have reconsidered the Markowitz portfolio formulation and have proposed countless of improvements and alternatives such as robust optimization methods, alternative measures of risk, regularization via sparsity, improved estimators of the covariance matrix, robust estimators for heavy tails, factor models, volatility clustering models, risk-parity formulations, index tracking, etc. This course will explore the Markowitz portfolio optimization in its many variations and extensions, with special emphasis on Python programming.

## System Modeling, Analysis and Control
>This course introduces basic concepts, tools and techniques for modeling, analysis, and control of dynamical systems. The course starts from the use of differential equations to model continuous time systems. Examples from a variety of Electronic and Computer Engineering disciplines will be given to illustrate the modeling process. Then, basic tools needed for analyzing the behavior of dynamical systems will be presented. Finally, techniques for controlling their behavior will be introduced. Throughout the course, laboratory experiments demonstrating the use of these analysis/design tools will be included.

## Machine Learning and Information Processing for Robotics
>The course is to introduce the basic concepts of information processing techniques used in robotics. Course content include Bayes theory, hidden Markov model, localization and mapping, kernel methods for regression, Gaussian process, classification, support-vector machine (SVM); common sensors, software platform and algorithms used in robotics research.

## Introduction to Embedded Systems
>This course is designed to teach techniques on how to integrate machine-level software and hardware in ARM-core microcontroller based systems. It makes use of industry-standard techniques and technologies, from which students can interface, design and program microcontroller systems. The task of the course will be to complete five laboratory experiments which address different aspects of hardware/software interfacing, and one large microprocessor/microcontroller based project which should result in the design and implementation of a small working embedded system.

## Digital Fundamentals and System Design
>Design and synthesis of digital circuits with main emphasis on sequential logic taught through project-based learning approach. Laboratory assignments make extensive use of VHDL and FPGAs and prepare students for an open-ended project undertaken in the remaining part of the course.

## Introduction to Integrated Circuits and Systems
>This course presents an overview, applications, fundamentals and design flow of the state-of-the-art integrated circuits (IC) and systems. Course contents include fabrication process; diodes, bipolar transistors and MOS transistors and modes of operations; and fundamental of analog, digital and mixed-signal IC design.

## Introduction to Smart Electric Power Systems
>This is an introductory course for electric power systems and smart grid. The course includes the following topics: power concepts for ac systems, generation, transmission, distribution, and utilization of electric power, system aspects of synchronous machines, transmission lines, transformers, and motors. Power flow and contingency states. Smart grid concepts, role of information technology in smart grid applications, smart metering, smart buildings and homes.

## Microelectronic Devices and Technology
>This is an introductory course for semiconductor device operation principles and technology in common electronic products such as integrated circuit (IC), digital camera, solar cell, memory elements, smartcard, etc. Topics covered include Semiconductor properties, IC fabrication technology, PN junctions, Bipolar Junction Transistors (BJT), MOSFETs, CCD and the future technology trend in the electronic industry.

## Electromagnetics: From Wireless to Photonic Applications
>This area course introduces applied electromagnetics from fundamentals to applications. Topics include: Gauss', Faraday's and Ampere's laws; electrostatics and magnetostatics; Maxwell's equations; electromagnetic plane wave propagation; transmission lines; radiation and antenna fundamentals; light wave fundamentals. Students will also acquire hands-on experience to electromagnetics through laboratory sessions.

## Digital Communications and Wireless Systems
>Representation of signals, optimum detection of signals in noise, matched filtering, error probability calculations for digital modulation. Multilevel modulation schemes, comparison of digital communications systems, mobile and wireless channels, diversity techniques, spread-spectrum communications, Resource Partitioning in Multiuser systems (FDMA, TDMA, CDMA) and their applications in cellular mobile and wireless personal communications.

## Machine Learning on Images
>This course introduces methods to process images on a computer. Topics include the formation and quantification of digital images, morphological image processing, image enhancement in the spatial and frequency domain, image restoration, color image processing, image compression, image segmentation, image representation and description, the image pattern classification using classic machine learning approaches, such as minimum-distance, and Bayes classifiers, Support Vector Machine et al., the modern approaches implemented using deep neural networks. This course provides a new perspective of comparing image processing technique to human vision system in terms of information perception and decision making. Students are expected to obtain knowledge of digital image processing, and hands-on experience on programming and presentation skill through the final project. This course is mathematics-oriented. It requires basic knowledge of linear algebra, calculus and linear filtering. Familiarity with the programming language MATLAB is needed.

## Information Theory and Error-Correcting Codes
>Communication and information theory; self and mutual information measures; channel models and capacity; source coding; hamming codes; cyclic codes; BCH and Reed-Solomon codes; convolutional codes and the Viterbi algorithm; burst error correction; Turbo coding.

## Control System Design
>In the lectures, the following topics will be covered: time-domain and frequency-domain system modeling and analysis, optimal control, robust control, computer aided control designs, digital control. In the experiments, the students will be asked to design and implement controllers for a magnetic suspension system, an inverted pendulum system, and a tower crane system.

## Introduction to Robotics: From Mobile Robots to Manipulators
>This course introduces basic building blocks of robots: actuators (DC and servo motors), sensors (proprioceptive/exteroceptive, passive/active); controller platforms as well as mechanical modules; and basic concepts of robotics: rigid motion and configuration space, kinematics, dynamics, trajectory generation and planning, locomotion, localization and mapping, navigation and control. Using these basic building blocks and robotic concepts, students will learn how to design and build a robot prototype that meets certain design specifications. Design examples include a mobile robot to engage in a competition, a robotic manipulator in a typical assembly task, an unmanned aerial vehicle (UAV) in a surveillance application, etc.

## Deep Learning for Natural Language Processing
>This course covers the basic theories and applications of natural language processing including speech processing using deep learning. It also introduces the topic of ethics in Artificial Intelligence. Topics include distributional semantics with word embeddings, text classification, emotion recognition, sentiment analysis from text and speech, language modeling, machine translation, and question answering. We will also cover multi-linguality and multi-modality, end-to-end chatbots, and task-oriented dialogue systems. The topics in Deep Learning ranges from feed forward neural networks, convolutional neural networks, recurrent neural networks, sequence-to-sequence neural networks, and the latest architecture in DL. Students will learn about various natural language processing (NLP) topics, how to design and build a deep learning model using PyTorch and Python, and the basics of software engineering. At the end of the course, students will work alone or in pairs to implement a deep learning model for various NLP research tasks, and describe their methods and results in a conference paper format. Successful groups will be able to submit their papers to an international conference.

## Deep Learning in Computer Vision
>Deep learning has significantly advanced the performance of computer vision system from object recognition to image processing. This course covers the basics and various applications of deep learning in computer vision. Students will study the details of convolutional neural networks as well as recurrent neural networks and train deep networks with end-to-end optimization, and learn deep learning based approaches for both high-level and low-level computer vision tasks such as image recognition and image enhancement. Through programming projects, students will implement, train, and test deep neural networks on cutting-edge computer vision research. Students would be required to study or do research in a final course project related to deep learning and computer vision and present their work by the end of the course.

## Robotic Manipulation and Mobility
>This course provides an overview of the techniques that enable robots to interact with the world, that is, robotic manipulation and locomotion. Fundamental theories and models regarding the two important problems will be introduced. Hands-on experience concerned with some of the topics to be covered will also be provided through term projects and assignments.

## Embedded System Design
>In this course, students will learn the important concepts and modern design practices of embedded computing systems. They will see how a complex embedded system can be systematically developed as a union of software and hardware. The course will cover several fundamental topics, such as design targets, hardware/software co-design methodology, common design techniques, processors, architectures, and physical implementations. It will also cover several advanced topics, such as behavioral modeling, low-power techniques, and systems-on-chip.

## FPGA-based Design: From Theory to Practice
>This course introduces the basic theory and design skills for FPGA-based design. The course aims to equip the students with enough knowledge and skills for the real world engineering using FPGA devices. Major topics include introduction to reconfigurable computing, hardware description language, FPGA device, and mapping flow. Students will gain hands-on experiences of the complete FPGA-based design cycle, from design specification, synthesis, implementation and simulation in this course.

## Mobile Embedded Systems: Hardware Platform, Software Development, and Applications
>This course introduces the hardware platform, the OS and software development platforms, and applications of Android-based smartphones and tablets. It will cover: hardware platforms of smartphones/tablets and their key components, such as mobile processors, communications chips, display, touchscreen, graphics, camera, battery, GPS, and various sensors; tutorials of Android and applications development on Android; latest applications, such as augmented reality, location based service, mobile TV, mobile health, mobile social network, handheld games, mobile computer vision, etc; low power hardware and software design techniques.

## CMOS VLSI Design
>CMOS process and design rules; MOS device electronics; CMOS circuit and logic circuit characterization and performance estimation; VLSI design and verification tools. Laboratory work will be centered on industry standard tools.

## Analogue Integrated Circuits Design and Analysis
>Multiple-stage operational amplifiers, frequency response, feedback analysis, stability and compensation, Slew rate, advanced amplifier design techniques, analog VLSI building blocks.

## Integrated Power Electronics
>Power computation, diodes and rectifier circuits, power factor correctors, switch mode power converters, magnetic components, switch capacitor power converters, linear regulators, and integrated circuit techniques for controller design.

## Semiconductor Materials and Devices
>This is an introductory course for semiconductor materials and devices. The course content includes the following topics: the growth and properties of semiconductor crystals; the theory of the electronic structures of atoms and solids; the energy band and conduction mechanisms in semiconductors; the physics of junction diodes; excess carriers; bipolar junction transistors (BJT); metal oxide semiconductor field-effect transistors (MOSFET).

## Integrated Circuit Fabrication Technology
>For UG students only. The course is intended to provide students with fundamental knowledge in device and integrated circuits (IC's) fabrication. The class covers the modules of device fabrication (including clean room concept, cleaning procedures, diffusion, lithography, wet processing, dry etching, chemical vapor deposition, sputtering) and process integration to form IC's. The lab section will bring the students with hands-on experience in IC fabrication facilities in Nanoelectronics Fabrication Facility.

## Fundamentals of Photovoltaic and Renewable Energy
>Introduction of solar and other renewable energy generation. Silicon and other semiconductor solar cells. Physics and circuit modeling. Energy storage and distribution.

## Engineering Optics
>An introductory course in optics covering fundamentals of geometrical and physical optics. Topics include: review of geometrical optics, first order optical system and analysis, aberration, aperture and field stops; Basic wave theory, diffraction, interference, polarization, dispersion; fundamentals of optical instrumentation.

## Photonics and Optical Communications
>To introduce optoelectronics and fiber optics for communications. Topics include optical fibers, optical sources, optical detectors, and passive components for wavelength-division multiplexing. Laboratory gives hands-on experience in handling optical fibers, lasers and detectors, micro-optical components, opto-mechanical equipment, and building wavelength-division-multiplexed optical links.

## Radio Frequency Engineering
>Techniques of radio-frequency/microwave circuit technology. S-parameter design of passive components; computer-aided analysis and design of microwave circuits. Component structures such as microstrip lines, waveguides, power divider and directional combiner, resonators and filters.

## Introduction to Biosensors and Bioinstrumentation
>This course builds on the fundamental knowledge of biosensors and bioinstrumentation. Lectures and hands-on laboratory experiments cover: (1) Basic concepts of biomedical signal analysis; (2) Measurements of bioelectrical, biomechanical and biochemical signals for medical diagnosis and clinical monitoring; (3) Principles of biosensors and biochips; (4) Simple design of new bioinstrumentation and biosensor to solve biomedical problems.

## Medical Imaging
>This course introduces medical imaging methods to senior undergraduate and graduate students. It covers the following topics: radiation, radiography, computer tomography, radioisotope imaging, diagnostic ultrasound imaging, magnetic resonance imaging, and applications of different imaging modalities. This course requires basic knowledge of linear algebra, calculus, and geometry. Familiarity with a programming language such as MATLAB is needed.

## Statistical Signal Analysis and Applications in Neural Engineering
>This is an introductory course on statistical signal processing and its applications in neural engineering. The course introduces the fundamentals of statistical signal processing, principles of neuroscience, and the technologies and implementations of neural engineering. The topics include probability, random variables, vectors and process, expectation, cellular mechanisms and neuroanatomy of the brain, neural coding theory, neural network models, plasticity and learning, neural interfaces and rehabilitation.


# Undergraduate Chemistry
## Fundamentals of Organic Chemistry
>Various classes of organic compounds, emphasizing organic chemical reactions and mechanisms of major functionalities and their importance in the area of biological chemistry. 

## Chemistry for Advanced Solar Cell Technologies
>Solar Cells are considered as one of the most promising renewable energy technologies. Conventional solar cells are based inorganic materials such as Si. In the past decade, however, several new solar cell technologies based organic materials are emerging as promising alternatives to conventional solar cells. In many of these advanced solar cell technologies, chemistry has been playing an important role. For example, in Polymer Solar Cells, it is critical to design and synthesize organic and polymer materials with unique photovoltaic and charge-transporting properties. This course will give an overview of several important solar cell technologies including Si cells, polymer solar cells, and dye-sensitized cells. The chemistry components of this course include how to design chemical structures to achieve photovoltaic and charge-transporting properties, and how to apply chemistry principles to understand the structures and properties of solar cell technologies. 


# Undergraduate Environment
## Green Buildings and Energy Efficiency
>This is an introduction to Green Buildings and their Energy Management. The course will consider Green Building attributes together with their economic, social and environmental impacts. Emphasis will be given to their energy conservation and resulting Carbon Dioxide emission reductions.

## Sustainable Development
>Sustainable development integrates improvements in human welfare with improvements in the health of the environment. It is societies attempt to solve the degradation that economic and social development has imposed on the environment. To solve environmental crises such as climate change, pollution, or destruction of biodiversity we need to integrate environmental practices into all our activities, pulling together new technologies, lifestyles, economic theories and business practices, and government policies. This course looks at how this process of integration works at the international, national, and municipal levels and from the organization perspectives of different industrial sectors, businesses, and communities.

## Energy Sources and Usage
>This course provides students the opportunity to enhance their interdisciplinary understanding of different types of energy resources and their local, regional, and global use. While the focus is on specific fuels and their respective technologies and systems, the course also includes topics on energy transition, energy efficiency, and sustainable consumption. The course also embeds a critical evaluation of energy sources and use with respect to longer-range energy security concerns and contemporary environmental concerns across scales especially the climate emergency.




# Undergraduate Mathematics
## Multivariable Calculus
>Sequences, series, gradients, chain rule. Extrema, Lagrange multipliers, line integrals, multiple integrals. Green's theorem, Stoke's theorem, divergence theorem, change of variables.

## Linear Algebra
>Vector space, matrices and system of linear equations, linear mappings and matrix forms, inner product, orthogonality, eigenvalues and eigenvectors, symmetric matrix.

## Differential Equations
>First and second order differential equations, initial value problems, series solutions, Laplace transform, numerical methods, boundary value problems, eigenvalues and eigenfunctions, Sturm-Liouville theory.

# Undergraduate Computer Science
## Programming with C++
>This course covers programming and data structures using C++. In addition to basic programming concepts such as variables and control statements, students will learn about arrays, pointers, dynamic data allocation, linked lists, stacks, queues, binary trees, recursion, and the basics of object oriented programming.

## Object-Oriented Programming and Data Structures
>To learn the fundamental concepts and techniques behind object-oriented programming. They include: abstract data types; creation, initialization, and destruction of objects; class hierarchies; polymorphism, inheritance and dynamic binding; generic programming using templates. To learn the object-oriented view of data structures: linked lists, stacks, queues, binary trees, and algorithms such as searching and hashing.

## Machine Learning
>Fundamentals of machine learning. Concept learning. Evaluating hypotheses. Supervised learning, unsupervised learning and reinforcement learning. Bayesian learning. Ensemble Methods. Deep learning.

## Introduction to Natural Language Processing
>Human language technology for text and spoken language. Machine learning, syntactic parsing, semantic interpretation, and context-based approaches to machine translation, text mining, and web search.

# Undergraduate Mechanical Engineering
## Statics and Dynamics
>Fundamental course on the analysis of the equilibrium and dynamic behavior of mechanical systems. Statics: equilibrium of particles and of rigid bodies; distributed forces; analysis of structures, including, trusses, frames, cables and beams. Dynamics: kinematics of particles; kinetics of particles, Newton's second law, energy, momenta, impact dynamics; systems of particles; kinematics of rigid bodies; kinetics of rigid bodies in two and three dimensions. 

## Thermodynamics
>Fundamental concepts; pure substance; work and heat; control volume; Ideal and real gases. First and second laws of thermodynamics. Entropy. Elementary power and refrigeration cycles.

## Design and Manufacturing I
>Introduction to the engineering design process and engineering graphics; design specification, concept generation, and concept evaluation; geometric construction, sketching, orthographic projection, auxillary views, sectioning, dimensioning, tolerancing, and working drawing.

## Energy Conversion
>Thermodynamics of combustion, chemical equilibrium, refrigeration and mixtures of gases. Analysis of power generation, propulsion systems. Performance of modern steam plants, gas turbines, internal combustion engines and refrigeration plants.

## Control Principles
>Introduction to system equations, block diagrams, signal flow graphs, state-space systems, transient response using convolution integral, root locus and frequency response methods. Design by root locus, frequency response and state space method. Nyquist stability test.

## Electrical Technology
>Electromagnetic circuits, transformers, electromechanical energy conversion, DC machines, asynchronous and synchronous machines, special machines, transients and dynamics, three-phase circuits and power electronics, applications in electrical building services.

## Mechatronic Design and Prototyping
>This course's aim is to broaden the professional and engineering interests of students by enhancing their practicum/team-based experience through initiatives different from those of traditional lectures and tutorials. This is a project-based course to develop the students' knowledge/experience in designing and building a practical mechatronics system (formerly called Industrial Training). Students will work in teams to identify the needs for their designed prototype. Also, students will be given the opportunity to design and build various mechatronics components including electronic circuits, motors, sensors, etc. from CAD drawings, and practise their engineering knowledge through all laboratory sessions. The main goal is to develop and nurture skills in problem-solving, communication, interpersonal interaction, project and time management, etc. via the entire project.

## Introduction to Robotics
>Rigid body motion, forward and inverse kinematics, manipulator Jacobians, force relation, dynamics and position control robot manipulators, force control and trajectory generation, collision avoidance and motion planning, robot programming languages.



# Postgraduate Electrical Engineering
## Introduction to the Design & Implementation of Micro-Systems
>Introduction to the concept of micro-systems. Dimensional scaling and its implications. Multi-physics modeling. Micro-fabrication techniques. Introduction to Coventor, a numerical simulation package for micro-systems. The design, implementation and testing of a micro-device.

## Advanced Analog IC Analysis and Design
>Noise analysis; Advanced op-amp design techniques; Analog VLSI building blocks: multipliers, oscillators, mixers, phase-locked loops, A/D and D/A converters; Passive filter design; Frequency scaling; Active filter design.

## Advanced CMOS Devices
>Principles and characteristics of semiconductor devices found in State-of-the-Art ICs. Emphasis is on deep-submicron MOS device design, characterization and modeling. Important issues such as short channel effects, high-field behavior, hot carrier effects, reliability and device scaling for present and future technology will be covered.

## Microelectronics Fabrication Technology
>Process technologies in IC fabrication: epitaxial growth; chemical-vapor and physical-vapor deposition of films; thermal oxidation; diffusion; ion implantation; microlithography; wet/dry etching processes; process integration of MOS and bipolar technologies.

## Advanced Photonics Technologies
>A brief review of modern optics theories, Fourier optics based devices and systems, fundamentals of laser physics, optoelectronics, nonlinear optics and laser spectroscopy.

## Nanoelectronic Materials for Energy Technologies
>Conventional and unconventional fabrication of nanostructures including electron beam lithography, nanoimprint, chemical synthesis, self-assembly, etc.; size dependent electronic and optoelectronic properties of nanomaterials; large-scale assembly and integration of nanomaterials for electronics; energy harvesting and storage devices using nanoelectronic materials.

## Semiconductor Power and Energy Conversion Technologies
>Analysis of power semiconductor device technologies in the context of electric power conversion and transmission; emphasis on the understanding of the critical roles of semiconductor device technologies in power and energy conversion. The mainstream silicon and emerging semiconductor power devices technologies; material properties, device structure design, advanced fabrication techniques, and device characteristics. Critical device-circuit interaction issues and basic power electronics circuits will be covered focusing on the role of these circuits in electric power conversion and transmission.

## Advanced Computer Architecture
>The course introduces the important building blocks in modern computing systems including superscalar processor pipeline, memory hierarchies, network design in the multicore‐processors. The design techniques, evaluation metrics and optimization techniques will be discussed in detail with the example of real computer systems. The students will gain not only theoretical knowledge through lectures, but also hands‐on experiences through projects.

## Digital VLSI System Design and Design Automation
>Structured design styles; specification, synthesis and simulation using Hardware Descriptive Language (HDL); Structural chip design and system design; Circuit design of system building blocks: arithmetic unit, memory systems; clocking and performance issues in system design; Design-Automation tools and their applications.

## RF/Microwave Circuit Design and Measurement
>Introduction to techniques for analyzing, engineering and testing of circuits for RF/microwave frequencies using CAD tools. The lab provides hands-on CAD/simulation, building and testing of low-noise amplifier, mixer, VCO, filter, IF AGC, detectors and other circuits discussed in lecture.

## Solid State and Semiconductor Electronics
>Crystal Lattices; lattice vibration and thermal properties of crystals; free-electron theory; electrons in periodic lattices; carrier transport; metal semiconductor contacts and semiconductor surfaces; optical processes.

## Advanced Topics in Nanoelectronics
>Introduction to state-of-the-art development in the broad area of nanoelectronics, including concepts and devices for spin electronics and quantum information science. Students are expected to demonstrate the capability of applying fundamental principles to understand advanced electronic devices through hands-on homework projects.

## 0Novel Liquid Crystal Devices for Photonics and Displays
>Liquid crystals: symmetry and basic physical properties. LC materials and their physical-chemical characterization. Electro-optical Effects in Liquid Crystal Materials: dependence on LC symmetry and parameters, LC cell configuration and driving conditions. Liquid crystal photoalignment and photopatterning technology. Liquid Crystal Photonics Devices. New applications of liquid crystals: biomedical devices, terahertz imaging, biosensors, liquid crystal lasers. New liquid crystal displays: 3D, projection, flexible displays, transflective displays, advances in LCD technology. New trends in liquid crystal addressing: modern TFT technologies.

## Advanced Display Technologies
>Introduction of the human visual system, Colorimetry and photometry, Introduction of the modern TFTs, Modern AMLCD, AMOLED, Fluorescence and phosphorescence, Introduction of Electrophoretic displays, Color electrophoretic displays, Nano-material for displays, Electroluminescence and Photoluminescence, Quantum dot, Quantum rods, State-of-the-art development in the area of display technology: High-resolution displays (4k, 8k, and 10k), Local backlight dimming, Introduction to AR/VR display solutions, Holographic displays, Flexible displays etc.

## High Frequency Circuit Design
>High frequency circuit design for wireless applications. S-parameters, front-end amp, VCO, PLL, power amplifier, and integration issues will be covered.

## Stochastic Processes
>Borel/sigma fields. Sequences of random variables and convergence. Spectral factorization. Karhunen-Loeve Expansion. Stationarity, ergodicity and spectral estimation. Mean square estimation and Kalman filtering. Entropy. System identification.

## Principles of Digital Communications
>The aim of this course is to provide an in-depth treatment of the theoretical basis, analysis, and design of digital communication systems. The first half of the course will focus on the theoretical foundations of a basic digital communication system, including source coding, modulating and channel coding, and introductory information theory. The second half will deal with advanced techniques including orthogonal frequency division multiplexing (OFDM), multi-antenna communications, spread-spectrum communications, and cooperative communications.

## Random Matrix Theory and Applications
>This course gives an introduction to random matrix theory (RMT), which has become a very important tool in communication systems, signal processing and a wealth of (high dimensional) statistical applications. Topics include: introduction to RMT models in engineering; eigenvalue distributions; Wishart and related distributions; finite-dimensional and large-dimensional techniques. Applications include wireless communications, array processing, robust covariance estimation, principal component analysis, signal detection, data analysis applications to financial and biomedical engineering.

## Advanced Stochastic Optimization for Wireless Systems
>Stochastic Optimization plays a critical role in radio resource optimization of wireless networks, optimal control theory as well as financial engineering (portfolio optimization). This course will focus on the application of stochastic optimization theory to the design and optimization of next generation wireless systems such as 5G systems. Topics covered include review of information theory for wireless fading channels, MIMO spatial diversity and spatial multiplexing, multi-user communication theory, classifications and motivating examples of stochastic optimizations (robust optimizations, delay-optimal wireless resource control), stochastic learning, stochastic gradient, stochastic stability and markov decision process.

## Convex Optimization
>Convex optimization theory with applications to communication systems and signal processing: convex sets/functions/problems; Lagrange duality and KKT conditions; saddle points and minimax problems; numerical algorithms; primal/dual decomposition methods. Applications: filter design; robust beamforming; power control in wireless systems; design of MIMO systems; GP duality in information theory; network utility maximization. For PG students in second year or above.

## Switch Mode Power Converters
>DC-DC conversion: topologies, continuous and discontinuous conduction modes, steady state analysis, loop gain analysis and relevant mathematical tools, stability and compensation; AC-DC conversion: power factor correctors.

## Power Management Integrated Circuit Design
>Integrated circuit techniques for power management components such as voltage references, linear voltage regulators, low dropout regulators, switch mode power converters and switched-capacitor power converters.

## Mixed-Signal Integrated Bio-Sensory Circuit Design
>The course aims to systematically introduce major issues of mixed-signal circuit designs and their applications in bio-medical and sensory systems. The first half course is dedicated to mixed-signal IC design. The course starts with 2 review classes on OPAMP design, filter design and circuit noise. Then, the course covers topics on pipelined ADC, Sigma-delta ADC, and SAR ADC. The second half course is dedicated to sensory and bio-medical IC design. The topics include bio-potential detection, implants, DNA detection, CCD, CMOS imaging, and CT/SPECT.

## High Tech Innovation and Entrepreneurship
>This interdisciplinary class combines a technical survey of emerging technologies/innovation with practical high-tech entrepreneurship training. It surveys a few major areas of innovation that will change the future landscape of the high-tech industry, with notable guest lecturers describing business cases and providing an industrial perspective. The class also introduces practical entrepreneurship principles for business development. Students will learn important skills such as building teams and attracting talent, developing a product/technology roadmap, marketing and selling an idea, company structuring, managing rapid growth, venture fund raising, forming strategic partnerships, and developing and intellectual property strategy. Students will form multi-disciplinary teams to write real-world business plans. Each team will develop a business model and execution plan based on its members' interests.

## Linear-System Theory
>Introduces modern system theory, with applications to control, signal processing and related topics. Basic system concepts, state-space and I/O representation, properties of linear systems, controllability, observability, minimality, transfer-function matrices, state and output feedback, stability, observers, optimal regulators.

## Robot Manipulation
>Extensive introduction to robot manipulation theory from a geometric viewpoint. Rigid-body kinematics; spatial and body representation of rigid-body velocities; coordinate transformations; forward kinematics of open-chain manipulators; solution of inverse kinematics; robot workspaces; nonlinear decoupling control and force control.

## Introduction to Networked Sensing, Estimation and Control
>The course gives an introduction to the analysis and design of sensing, estimation and control systems in a networked setting. It consists of three parts: the first part introduces necessary background knowledge in communication networks, sensor networks, linear state estimation, MAP and ML estimators, Kalman filtering, and modern control theory; the second part focuses on analysis of network effect to remote state estimation and control; the third part presents some advanced topics including distributed state estimation and resource allocation through scheduling.

## Introduction to Aerial Robotics
>This course gives a comprehensive introduction to aerial robots. The goal of this course is to expose students to relevant mathematical foundations and algorithms, and train them to develop real-time software modules for aerial robotic systems. Topics to be covered include rigid-body dynamics, system modeling, control, trajectory planning, sensor fusion, and vision-based state estimation. Students will complete a series of projects which combine into an aerial robot that is capable of vision-based autonomous indoor navigation.

## Robot Perception and Learning
>This course introduces the essential theoretical frameworks, methods, concepts, tools and techniques used to enable robotic perception and behavior, with particular emphasis on applications in autonomous mobile robots. The course starts from Bayesian programming and probabilistic methods, and then moves on to cover generic machine learning, especially deep learning. It also includes coverage of reinforcement learning. Important libraries for hands-on experiments for mobile robotic systems will be introduced. The students will have the opportunity to test their algorithms and implementations on real platforms.

## Advanced Deep Learning Architectures
>This course focuses on advanced deep learning architectures and their applications in various areas. Specifically, the topics include various deep neural network architectures with applications in computer vision, signal processing, graph analysis, and natural language processing. Different state-of-the-art neural network models will be introduced, including graph neural networks, normalizing flows, point cloud models, sparse convolutions,and neural architecture search. The students have the opportunities to implement deep learning models for some AI-related tasks such as visual perception, image processing and generation, graph processing, speech enhancement, sentiment classification, and novel view synthesis.

## Introduction to Bioinformatics Algorithms
>This is an introductory course on computational biology at the molecular level. It will cover basic biological knowledge, important biological questions, common data acquisition techniques, popular data analysis algorithms and their applications. The major content of this course is computation-oriented.

## Microfluidics and Biosensors
>Introduction to Microfluidics and Biosensors; Overview of microfabrication materials & techniques; microfluidic principles; miniaturized biosensors; micro total analysis system (µTAS) & lab-on-a-chip (LOC) for clinical and research applications.



#### Reference

- https://prog-crs.hkust.edu.hk/ugcourse
- https://prog-crs.hkust.edu.hk/pgcourse
- http://stellar.mit.edu/index.html