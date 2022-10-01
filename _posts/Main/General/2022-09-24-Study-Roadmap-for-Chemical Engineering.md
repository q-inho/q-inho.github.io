---
title:  "Study Roadmap for Chemical Engineering"
excerpt: "Chemical Process Design, Chemical Product Design, Environmental Engineering and others.."

categories:
  - General
tags:
  - [Chemical Engineering]

toc: false
toc_sticky: false
 
date: 2022-09-24
last_modified_at: 2022-10-02
---

# My Roadmap for Chemical Engineering

<div class="mermaid"> 
      graph LR
        CENG2110[Process and Product Design Principles]
        CENG2210[Chemical and Biological Engineering Thermodynamics]
        CENG2220[Transport Phenomena I]
        CENG2310[Moedling for Chemical and Biological Engineering]
        CENG2110 --> CENG3110[Process Dynamics and Control]
        CENG2110 --> CENG3120[Process Design and Integration]
        CENG2110 --> CNEG3150[Integrated Chemical Process and Product Design]
        CENG2110 & CENG2210 --> CENG3210[Separation Processes]
        CENG2220 --> CENG3220[Transport Phenomena II]
        CENG3230[Chemical and Biological Reaction Engineering]
        CENG2310 --> CENG3300[Data Science for Molecular Engineering]
        CENG2110 --> CENG4130[Plant Design and Economics]
        CENG2210 --> CENG4140[Energy Resources, Conversion and Technologies]
        CENG2220 & CENG3210 & CENG3230 --> CENG4150[Product and Process Design in Chemical and Biological Engineering]
        CENG3210 & CENG3230 --> CENG4540[Nanomaterials and Applications in Chemical Engineering]
        CENG4620[Biproducts and Processing]
        CENG4630[Food Processing Technology]
        CENG2210 & CENG3230 --> CENG4640[Biomolecular Engineering]
        CENG3210 & CENG3230 --> CENG4670[Pharmaceutical Engineering]
        CENG3210 & CENG3230 --> CENG4710[Environmental Control]
        CENG4720[Environmental Impact Assessment and Management Systems]
        MATH2121[Linear Algebra]
        MATH2023[Multivariable Calculus]
        BIEN2410[Cellular and Systems Physiology for Engineers]
        BIEN2610[Chemical Biology for Engineers]
        CHEM2111[Fundamentals of Organic Chemistry]
        CHEM2311[Analytical Chemistry]

        subgraph Advanced Study
        CENG5100[Advanced Reaction Engineering]
        CENG5210[Advanced Separation Processes]
        CENG5220[Numerical Methods for Chemical Engineering]
        CENG5230[Advanced Control and Data Science]
        CENG5300[Advanced Chemical Engineering Thermodynamics]
        CENG5520[Polymer and Materials Characterization Techniques]
        CENG5530[Physical and Rheological Behavior of Polymers]
        CENG5550[Polymer Physics and Advanced Applications]
        CENG5610[Protein Engineering]
        CENG5840[Nanomaterials for Chemical Engineering Applications]
        CENG5930[Electrochemical Energy Technologies]
        end

        CENG3230 --> CENG5100
        CENG3210 --> CENG5210
        MATH2121 --> CENG5220
        CENG2210 --> CENG5300
        CENG3210 & CENG3230 --> CENG5840

        subgraph Chemical and Environmental Engineering
        CIVL4450[Carbon Footprint Analysis and Reduction]
        ENEG4320[Energy Storage Technology]
        ENVR3110[Sustainable Development]
        ENVR3220[Energy Source and Usage]
        CIVL4470[Air Quality Control and Management]
        ENEG3220[Energy Initiatives Forging Future Engineers]
        ENVR3210[Environmental Technology]
        ENVR2010[Environmental Science Fundamentals]
        ENVR2030[Material and Energy Balance for Environmental Management]
        end

        ENVR3210 --> CIVL4450
        CENG2210 --> ENEG4320
        ENVR2010 & ENVR2030 --> ENVR3210


</div>

---

# Undergraduate Chemical Engineering
- Process and Product Design Principles
- Chemical and Biological Engineering Thermodynamics
- Transport Phenomena I
- Modeling for Chemical and Biological Engineering
- Process Dynamics and Control
- Process Design and Integration
- Integrated Chemical Process and Product Design
- Separation Processes
- Transport Phenomena II
- Chemical and Biological Reaction Engineering
- Data Science for Molecular Engineering
- Plant Design and Economics
- Energy Resources, Conversions and Technologies
- Product and Process Design in Chemical and Biological Engineering
- Nanomaterials and Applications in Chemical Engineering
- Bioproducts and Processing
- Food Processing Technology
- Biomolecular Engineering
- Pharmaceutical Engineering
- Environmental Control
- Environmental Impact Assessment and Management Systems

# Undergraduate Bioengineering
- Cellular and Systems Physiology for Engineers
- Chemical Biology for Engineers

# Undergraduate Chemistry
- Fundamentals of Organic Chemistry
- Analytical Chemistry

# Undergradaute Civil Engineering
- Carbon Footprint Analysis and Reduction
- Air Quality Control and Management

# Undergraduate Energy
- Energy Initiatives Forging Future Engineers
- Energy Storage Technology

# Undergraduate Environment
- Environmental Science Fundamentals
- Material and Energy Balance for Environmental Management
- Sustainable Development
- Environmental Technology
- Energy Source and Usage

# Undergraduate Mathematics
- Multivariable Calculus
- Liner Algebra

# Postgraduate Chemical Engineering
- Advanced Reaction Engineering
- Advanced Separation Processes
- Numerical Methods for Chemical Engineers
- Advanced Control and Data Science
- Advanced Chemical Engineering Thermodynamics
- Polymer and Materials Characterization Techniques
- Physical and Rheological Behavior of Polymers
- Polymer Physics and Advanced Applications
- Protein Engineering
- Nanomaterials for Chemical Engineering Applications
- Electrochemical Energy Technologies

---

# Details
## Process and Product Design Principles
<details>
<summary>Study material</summary>
<div markdown="1">
- *Textbook* by Author
</div>
</details>
>Processes and process variables, engineering data, and process representations. The conservation principle. Material and energy balances on non-reactive and reactive unit operations and process systems with recycles. Introduction to chemical product design

## Chemical and Biological Engineering Thermodynamics
>First law of thermodynamics for closed and open systems, enthalpy and the energy equation. PVT data and thermodynamic properties, methods for their estimation, phase equilibria. Second and third laws of thermodynamics, entropy and the Carnot engine. Examples from chemical and biological processes

## Transport Phenomena I
>Fundamentals of transport phenomena with emphasis on physical properties, flow behavior and diffusive transport of fluids in chemical and biological systems. Engineering derivation and quantitative analysis of fluid transport in confined domains. Emphasis on practical application of transport phenomena in chemical and biological engineering. Use of software for solving problems in transport phenomena.

## Modelling for Chemical and Biological Engineering
>Modeling of physical, chemical and biological processes. Balance Equations. Dimensional and scaling analysis. Analytical and numerical solutions to initial and boundary value problems. Use of computer tools for engineering calculations. This course uses examples in the Chemical or Environmental Engineering disciplines. 

## Process Dynamics and Control
>Basic concepts, mathematical model, transfer function. Dynamics of first - and higher-order systems. Feedback control, controller tuning, frequency response methods. Cascade control, feedforward and ratio control. Introduction to computer control and multi-variable control. Control and instrumentation hardware.

## Process Design and Integration
>Conceptual design of chemical processes. Flowsheet synthesis, selection and analysis. Short-cut methods, steady-state simulation, computer-aided design tools. Heat-exchanger networks, energy integration. Batch and continuous process design. Case studies and non-traditional applications.

## Integrated Chemical Process and Product Design
>Conceptual design of chemical processes and products. Integration of prior knowledge in the execution of a structured design project, under the direct guidance of faculty. Project topics encompass both process and product design with different emphases. Design tasks include literature and market survey, ideation, feasibility and viability studies, prototyping and/or simulation, unit operation or component design, planning and project management, and societal and environmental impact assessment. Emphasis on the design process, hands-on experimentation, teamwork, and self-learning.

## Separation Processes
>Phase equilibria. Ideal and nonideal mixtures. Thermodynamic properties and VLE from equations of state. Liquid-liquid and liquid-solid systems. Stage process, short-cut and rigorous calculations in absorption, distillation or extraction. Continuous contacting processes. Separation sequences. Simulation and design.

## Transport Phenomena II
>Application of transport phenomena in chemical processes. Fluid flow in pipes and channels. Conductive, forced and free convective, and radiative heat transfer. Diffusive and convective mass transport. Coupling of transport and chemical reactions. Analysis and design of heat exchangers and contacting processes for separation and reaction. Numerical solutions and simulations of complex systems.

## Chemical and Biological Reaction Engineering
>Stoichiometry and reaction equilibria. Homogeneous reactions kinetics. Mole balances: batch, continuous-stirred tank and plug flow reactors. Collection and analysis of rate data. Catalytic and enzymatic reaction kinetics and reactor design. Diffusion effects. Examples from chemical and biological processes.

## Data Science for Molecular Engineering
>Mathematical methods for data science; Data processing and presentation; Supervised learning, including nearest neighbor methods, linear and nonlinear regression; Introduction to deep learning and neural networks.

## Plant Design and Economics
>Computer-aided-design and process evaluation. Risk assessment, qualitative and quantitative assessment. Hazop, Hazan, FMEA, decision tree, fault tree, reliability. Toxicity, dispersion, fire, explosion, relief. Workplace safety. Plant safety and hazard analysis. Plant equipment specification and selection. Cost estimation and profitability analysis. Project evaluation. Cost optimization. Environmental control.

## Energy Resources, Conversions and Technologies
>The course will provide the fundamental knowledge of energy resources, their conversions and utilization technologies.Basic thermodynamics such as fuel and combustion models, measurement techniques will be taught to enable students to manage basic conversion calculations and to evaluate different energy utilization options. The course will also cover topics in green energies and fuels, providing an outlook of future energy uses.

## Product and Process Design in Chemical and Biological Engineering
>This course covers conceptualization, design, manufacture, and launch of chemical and biological products. These include molecular products, devices, functional, and formulated products. Relevant business and project management concepts are introduced.

## Nanomaterials and Applications in Chemical Engineering
>Introduction to nanostructured materials and nanotechnology. Synthesis and characterization of nanostructured materials. Selected applications of nanostructured materials in chemical engineering.

## Bioproducts and Processing
>Survey of bioproducts, cellular production hosts, production techniques (bioreactors), separation and purification processes, product formulation, product and process design.

## Food Processing Technology
>Principles of Food Spoilage and Preservation, Thermal Processing (blanching, pasteurization, sterilization, aseptic UHT processing.), Chilling & Freezing, Dehydration, Separation and concentration, Fermentation, and concept of hurdle technology.

## Biomolecular Engineering
>Students not studying in the Department of Chemical Engineering may enroll in the course upon instructor's approval. Molecular biology, protein engineering, enzyme kinetics, thermodynamics and energetics of biological systems, molecular and cellular processes, bioreaction networks and metabolic engineering.

## Pharmaceutical Engineering
>Survey of western pharmaceuticals; pharmaceutical processing technologies including reactions and separations; enantiomers and chiral separations; polymorphs and solid state pharmaceuticals; pharmaceutical dosage forms including tablets, capsules and transdermal patches; traditional Chinese medicine processing.

## Environmental Control
>Wastes from the process industries. Behavior of toxic chemicals in atmospheric, soil and aquatic environments. Adsorption/desorption, air stripping, steam stripping, supercritical extraction. Pyrolysis, biological, catalyzed and uncatalyzed reactions. Integrated environmental control. 

## Environmental Impact Assessment and Management Systems
>This course will review the methods for assessing environmental impacts. Impact and management systems will be discussed in the context of both HK and international environmental legislation, which incorporates Licensing, BATNEEC, integrated pollution control, environmental management and auditing systems based on ISO 14000. Actual case studies from the process industries will be discussed.

## Cellular and Systems Physiology for Engineers
>Essential cellular and systems physiology for engineers. Hierarchical organization of a complex organism: from organelles to organ systems. Cellular physiology, neurophysiology, vision, muscle and movement, and the cardiovascular system.

## Chemical Biology for Engineers
>A concise introduction of biochemistry, cell biology, and pharmacology to engineers. Molecular and supramolecular building blocks of biological systems. Analysis and engineering of biological systems by chemical principles. Introduction to transcriptomics, proteomics and metabolomics.

## Fundamentals of Organic Chemistry
>Various classes of organic compounds, emphasizing organic chemical reactions and mechanisms of major functionalities and their importance in the area of biological chemistr

## Analytical Chemistry
>Fundamental and practical aspects of chemical analysis, including titrimetric, electrical, optical and mass spectroscopic methods, analytical separations by chromatography. 

## Carbon Footprint Analysis and Reduction
>This course aims to provide students with an understanding of the sources and impacts of climate change, national and international policies, Kyoto Protocol, carbon credits and offset concepts. As engineers to be, students will also be able to calculate organization's carbon footprint, identify suitable mitigation strategies and provide carbon reduction solutions.

## Air Quality Control and Management
>Historical and health impact studies related to air pollution. Atmospheric stability and its impact on the transport and dispersion of pollutants. Sources of major air pollutants. Comparison of urban, industrial and transport related air pollution issues, using Hong Kong and Pearl River Delta as examples. Control of stationary and mobile emission sources. Air quality management - framework, policy tools and comparison of different approaches.

## Energy Initiatives Forging Future Engineers
>This course aims to develop a new knowledge-delivery approach to the engineering students. The course will involve cross-border universities, giving a study on various aspects and future prospective in the energy engineering sectors. Faculty members from both universities will divide into two main parts including the future prospective of various kinds of energy technologies and the case studies of different studies. 

## Energy Storage Technology
>Electrochemical energy conversion and storage technologies such as fuel cells, batteries, electrolyzers, supercapacitors, solar cells, CO2 reduction, etc. help overcome the energy and environmental problems that have become prevalent in our society. This course will deliver the electrochemistry fundamentals first and then focus on the principles, critical materials, limitations, current status and development trend for each technology.

## Environmental Science Fundamentals
>Understanding our environment, including the ecology, biodiversity and cycles of environmental ecosystems, human environmental impacts such as climate change, energy use, chemical toxicology, waste disposal, water and air pollution; conservation; exploration of new green technologies to reduce impacts, environmental law and changes in policies to ensure sustainability. Case studies through group projects.

## Material and Energy Balance for Environmental Management
>Material and energy balance provides a quantitative account for materials and/or energy redistribution when changes happen. It is a tool which can be used to predict or solve practical problems like pollution control and management, product life-cycle analysis and management of resources (e.g. energy, food and water) for sustainable development. This course will introduce students to the fundamental principles of material and energy balance as applicable to environmental management. Covered topics include pollution control and treatment and industrial/building energy management. 

## Sustainable Development
>Sustainable development integrates improvements in human welfare with improvements in the health of the environment. It is societies attempt to solve the degradation that economic and social development has imposed on the environment. To solve environmental crises such as climate change, pollution, or destruction of biodiversity we need to integrate environmental practices into all our activities, pulling together new technologies, lifestyles, economic theories and business practices, and government policies. This course looks at how this process of integration works at the international, national, and municipal levels and from the organization perspectives of different industrial sectors, businesses, and communities.

## Environmental Technology
>This course emphasizes on the fundamental science and engineering principles of the innovation, design, development and application of environmental technologies for conservation and pollution abatement. The course covers both existing and emerging environmental technologies for the sustainable development including energy conservation and renewable energies, carbon neutral lifestyle, green building, manufacturing and processing, technologies for improved air, water, soil qualities, waste reduction and reuse, etc.

## Energy Sources and Usage
>This course provides students the opportunity to enhance their interdisciplinary understanding of different types of energy resources and their local, regional, and global use. While the focus is on specific fuels and their respective technologies and systems, the course also includes topics on energy transition, energy efficiency, and sustainable consumption. The course also embeds a critical evaluation of energy sources and use with respect to longer-range energy security concerns and contemporary environmental concerns across scales especially the climate emergency.

## Multivariable Calculus
>Sequences, series, gradients, chain rule. Extrema, Lagrange multipliers, line integrals, multiple integrals. Green's theorem, Stoke's theorem, divergence theorem, change of variables.

## Linear Algebra
>Vector space, matrices and system of linear equations, linear mappings and matrix forms, inner product, orthogonality, eigenvalues and eigenvectors, symmetric matrix.

## Advanced Reaction Engineering
>Reaction mechanisms and kinetics. Homogeneous and heterogeneous catalysis. Ideal reactors. Multiphase reactors. Interplay of reaction, mixing, heat and mass transfer. Design of reaction systems involving organics, inorganics, and polymeric materials. Experimental techniques in reaction engineering. Use of mathematical software to problem solving.

## Advanced Separation Processes
>Separation of gaseous and liquid mixtures by adsorption. Affinity chromatography. Membrane separation technology: reverse osmosis, ultrafiltration. Electrophoresis and other product recovery methods.

## Numerical Methods for Chemical Engineers
>This course discusses the application of various numerical methods to solve typical problems found in the chemical engineering discipline. Topics include systems of linear and non-linear algebraic equations, ordinary and partial differential equations, and numerical optimization. The aim is to equip students with a practical set of skills to solve mathematical problems that they may encounter in their research or chemical engineering profession.

## Advanced Control and Data Science
>The course will cover digital and advanced control methods such as adaptive, model predictive, and learning controls and methods of process monitoring and optimization in the context of big data environment.

## Advanced Chemical Engineering Thermodynamics
>The fundamental laws of thermodynamics, properties of pure substances and mixtures, phase and chemical equilibria, intermolecular forces. Brief introduction to statistical thermodynamics, colloid and interfacial phenomena, and molecular self-assembly.

## Polymer and Materials Caracterization Techniques
>The course will first review some basic concepts in polymer physics and polymer chemistry. The course focuses more in polymer and materials characterization and related fabrication toward applications of advanced and functional polymers. The characterization techniques include thermal analysis of differential scanning calorimetry (DSC), dynamic thermal mechanical analysis (DTMA), thermal gravimetric analysis (TGA), scanning electron microscopy (SEM), transmission electron microscopy (TEC), optical microscopy, infrared spectroscopy (FTIR), X-ray diffraction, surface analysis, and mechanical properties and testing. MCPR's instrument demo will also be arranged.

## Physical and Rheological Behavior of Polymers
>Linear and nonlinear viscoelastic behavior. Relaxation transitions and their relationships to molecular structures. Crystallization and melting of polymers. Mixing and swelling of polymers.

## Polymer Physics and Advanced Applications
>The course will provide students with a general understanding of the relationship of polymer structure and properties that may help them in selection and design of polymers for their research. Applications in engineering materials, membrane separations, and bioengineering will be discussed.

## Protein Engineering
>This course introduces fundamentals of protein science as well as rational design and evolutionary approaches for engineering protein molecules. Protein fundamentals provide the basic knowledge of protein structure and function. Rational design-based protein engineering use several case studies to illustrate the role of modern computational tools in design of functional protein molecules such as catalysts, biosensors, biomaterials, etc. Protein directed evolution topics cover mechanisms of biomolecular evolution, fitness landscapes, examples of successful protein evolution, and metabolic engineering enabled by directed evolution.

## Nanomaterials for Chemical Engineering Applications
>Nanomaterials and nanotechnology have become a rapid growth area in the 21st century. This course provides an introduction to students who enter into this exciting area of research. The course will focus on major routes for the synthesis of nanostructured materials. Selected applications of nanomaterials in chemical engineering applications, such as separation and catalysis, will be studied.

## Electrochemical Energy Technologies
>Electrochemical energy conversion and storage technologies such as fuel cells, batteries, supercapacitors, solar cells, electrolyzers, CO2 reduction, etc. help overcome the energy and environmental problems that have become prevalent in our society. This course will focus on the principles and critical materials for each technology. Cutting-edge research areas as well as electrochemistry fundamentals will be discussed in this course.





#### Reference

- https://prog-crs.hkust.edu.hk/ugcourse
- https://prog-crs.hkust.edu.hk/pgcourse
- http://stellar.mit.edu/index.html