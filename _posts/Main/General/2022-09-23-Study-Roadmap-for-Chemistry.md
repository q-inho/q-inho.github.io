---
title:  "Study Roadmap for Chemistry"
excerpt: "Biomolecular Chemistry, Environmental and Analytical Chemistry, Materials Chemistry, Pure Chemistry and others"

categories:
  - General
tags:
  - [Chemistry]

toc: false
toc_sticky: false
 
date: 2022-09-23
last_modified_at: 2022-10-23
---

# My Roadmap for Chemistry

<div class="mermaid"> 
      graph LR
        CHEM2110[Organic Chemistry I]
        CHEM2210[Inorganic Chemistry I]
        CHEM2310[Fundamentals of Analytical Chemistry]
        CHEM2409[Mathematical Methods for Physical Chemistry]
        CHEM2409 --> CHEM2410[Physical Chemistry I: Equilibrium Thermodynamics and Statistical Mechanics]
        CHEM3010[Great Ideas in Chemistry]
        CHEM3020[Chemistry in the Mass Media]
        CHEM2110 --> CHEM3120[Organic Chemistry II]
        CHEM2210 --> CHEM3220[Inorganic Chemistry II]
        CHEM2310 --> CHEM3320[Instrumental Analysis]
        CHEM2410 --> CHEM3420[Physical Chemistry II]
        CHEM3120 --> CHEM4110[Structural Elucidation in Organic Chemistry]
        CHEM3120 --> CHEM4120[Biomolecular Chemistry]
        CHEM3120 --> CHEM4130[Medicinal Chemistry]
        CHEM3120 --> CHEM4140[Intermediate Organic Chemistry]
        CHEM2110 & CHEM2409 --> CHEM4160[Cheminformatics]
        CHEM3220 --> CHEM4210[Solid State Chemistry]
        CHEM3220 --> CHEM4220[Materials Chemistry]
        CHEM2310 & CHEM2410 --> CHEM4230[Materials Characterization Method]
        CHEM3220 --> CHEM4240[Intermediate Inorganic Chemistry]
        CHEM2310 --> CHEM4310[Environmental Chemistry]
        CHEM2310 --> CHEM4320[Environmental Analytical Chemistry]
        CHEM2310 --> CHEM4330[Separation Science]
        CHEM2310 --> CHEM4340[Bioanalytical Techniques]
        CHEM3420 --> CHEM4410[Physical Chemistry in Biological Applications]
        CHEM2409 & CHEM2410 --> CHEM4420[Statistical Machine Learning Methods for Chemical Data Analysis]
        CHEM2110 & CHEM2210 & CHEM2410 --> CHEM4430[Symmetry in Chemistry and Spectroscopy]
        CHEM3220 --> CHEM4620[Organometallic Chemistry]
        CHEM2110 & CHEM2410 --> CHEM4640[Chemistry for Advanced Solar Cell Technologies]

        subgraph Biochemistry
        LIFS2010[Modern Approaches to Biochemical and Cell Biological Research]
        LIFS2040[Cell Biology]
        LIFS2060[Biodiversity]
        LIFS2070[Introduction to Biotechnology]
        LIFS2080[Plant Biology]
        LIFS2210[Biochemistry I]
        LIFS2220[Biochemistry II]
        LIFS3010[Molecular and Cellular Biology I]
        LIFS3020[Molecular and Cellular Biology II]
        LIFS3040[Animal Physiology]
        LIFS3060[Microbiology]
        LIFS3070[Introduction to Biophysical Instrumentation]
        LIFS3110[Biotechnological Application of Recombinant DNA Techniques]
        LIFS3140[General Genetics]
        LIFS3150[Biostatistics]
        LIFS3240[Introduction to Neurobiology]
        LIFS3580[Bioinformatics]
        LIFS4060[Immunobiology]
        LIFS4090[Developmental Biology]
        LIFS4140[Cancer Biology]
        LIFS4190[Cellular Signaling]
        LIFS4320[Data Science for Biology and Medicine]
        LIFS4370[Human Genetics and Personalized Medicine]
        LIFS4540[Structure and Function of Proteins]
        LIFS4620[Advanced Biological Chemistry]
        LIFS4760[Biochemistry of Diseases]
        LIFS4800[Epigenetics and Chromosomes Biology]
        LIFS4950[Neurochemistry]
        BIPH2010[Introductory Biological Physics]
        BIPH3010[Advanced Biological Physics]
        BIPH4010[Principles of Quantitative Instrumentation]
        COMP2011[Programming with C++]
        end

        LIFS2040 --> LIFS2080
        LIFS2210 & LIFS2220 --> LIFS3010
        LIFS2040 & LIFS2210 & LIFS2220 --> LIFS3020
        LIFS2040 --> LIFS3040
        LIFS2060 --> LIFS3060
        LIFS2040 --> LIFS3070
        LIFS2040 & LIFS2210 --> LIFS3110
        LIFS2040 --> LIFS3140
        LIFS2040 --> LIFS3240
        LIFS3140 --> LIFS3580
        LIFS3140 --> LIFS4060
        LIFS2040 --> LIFS4090
        LIFS3140 --> LIFS4140
        LIFS3020 --> LIFS4190
        COMP2011 & LIFS3150 & LIFS3140 --> LIFS4320
        LIFS3140 --> LIFS4370
        LIFS2210 --> LIFS4540
        LIFS2210 --> LIFS4620
        LIFS2040 --> LIFS4760
        LIFS2210 --> LIFS4800
        LIFS2040 --> LIFS4950
        BIPH2010 & LIFS2040 --> BIPH3010
        BIPH3010 --> BIPH4010



        subgraph Advanced Study
        CHEM5110[Advanced Organic Chemistry I]
        CHEM5120[Advanced Organic Chemistry II]
        CHEM5130[Asymmetric Catalysis]
        CHEM5160[Advanced Medicinal Chemistry]
        CHEM5210[Computational Chemistry]
        CHEM5220[Statistical Mechanics: Theory and Applications in Complex Systems]
        CHEM5230[Quantum Chemistry]
        CHEM5310[Advanced Inorganic Chemistry I]
        CHEM5340[Chemical X-ray Crystallography]
        CHEM5410[Atmospheric Chemistry]
        CHEM5420[Advanced Analytical Chemistry]
        CHEM5540[Chemistry for Advanced Materials]
        CHEM5880[Polymer Chemistry]
        end

        CHEM4140 --> CHEM5110
        CHEM5110 --> CHEM5120
        CHEM3120 --> CHEM5130
        CHEM4130 --> CHEM5160
        CHEM3420 --> CHEM5210
        CHEM2410 --> CHEM5220
        CHEM3420 --> CHEM5230
        CHEM3220 --> CHEM5310
        CHEM4210 --> CHEM5340
        CHEM3420 --> CHEM5410
        CHEM2310 --> CHEM5420
        CHEM4220 --> CHEM5540
        CHEM3120 --> CHEM5880


</div>

---

# Undergraduate Chemistry
- Organic Chemistry I
- Inorganic Chemistry I
- Fundamentals of Analytical Chemistry
- Mathematical Methods for Physical Chemistry
- Physical Chemistry I: Equilibrium Thermodynamics and Statistical Mechanics
- Great Ideas in Chemistry
- Chemistry in the Mass Media
- Organic Chemistry II
- Inorganic Chemistry II
- Instrumental Analysis
- Physical Chemistry II
- Structural Elucidation in Organic Chemistry
- Biomolecular Chemistry
- Medicinal Chemistry
- Intermediate Organic Chemistry
- Cheminformatics
- Solid State Chemistry
- Materials Chemistry
- Materials Characterization Method
- Intermediate Inorganic Chemistry
- Environmental Chemistry
- Environmental Analytical Chemistry
- Separation Science
- Bioanalytical Techniques
- Physical Chemistry in Biological Applications
- Statistical Machine Learning Methods for Chemical Data Analysis
- Symmetry in Chemistry and Spectroscopy
- Organometallic Chemistry
- Chemistry for Advanced Solar Cell Technologies

# Undergraduate Life Science
- Modern Approaches to Biochemical and Cell Biological Research
- Cell Biology
- Biodiversity
- Introduction to Biotechnology
- Plant Biology
- Biochemistry I
- Biochemistry II
- Molecular and Cellular Biology I
- Molecular and Cellular Biology II
- Animal Physiology
- Microbiology
- Introduction to Biophysical Instrumentation
- Biotechnological Application of Recombinant DNA Techniques
- General Genetics
- Biostatistics
- Introduction to Neurobiology
- Bioinformatics
- Immunobiology
- Developmental Biology
- Cancer Biology
- Cellular Signaling
- Data Science for Biology and Medicine
- Human Genetics and Personalized Medicine
- Structure and Function of Proteins
- Advanced Biological Chemistry
- Biochemistry of Diseases
- Epigenetics and Chromosomes Biology
- Neurochemistry

# Undergraduate Biological Physics
- Introductory Biological Physics
- Advanced Biological Physics
- Principles of Quantitative Instrumentation

# Undergraduate Computer Science
- Programming with C++


# Postgraduate Chemistry
- Advanced Organic Chemistry I
- Advanced Organic Chemistry II
- Asymmetric Catalysis
- Advanced Medicinal Chemistry
- Computational Chemistry
- Statistical Mechanics: Theory and Applications in Complex Systems
- Quantum Chemistry
- Advanced Inorganic Chemistry I
- Chemical X-ray Crystallography
- Atmospheric Chemistry
- Advanced Analytical Chemistry
- Chemistry for Advanced Materials
- Polymer Chemistry

---

# Details
## Organic Chemistry
<details>
<summary>Study material</summary>
<div markdown="1">
- *Textbook* by Author
</div>
</details>
>This is the first part of the organic chemistry course series designed for students taking a major/minor in chemistry/life science under the four-year degree. Topics covered include: structure and bonding; regio-, geometric, and stereoisomerism; polar and radical reactions of alkenes and alkynes; substitution and elimination reactions; synthesis and reactions of alcohols and epoxides.

## Inorganic Chemistry I
>Key topics include atomic structure, molecular structure and bonding, structures of simple solids, physical techniques in inorganic chemistry, molecular symmetry, acids and bases, introduction to coordination chemistry, electronic structures and spectra of coordination compounds.

## Fundamentals of Analytical Chemistry
>Fundamental and practical aspects of chemical analysis, including titrimetric, electrical and spectroscopic methods, analytical separations by GLC and HPLC.

## Mathematical Methods for Physical Chemistry
<details>
<summary>Study material</summary>
<div markdown="1">
- ***Mathematics for Physical Chemistry*** by Robert G. Mortimer
</div>
</details>
>This course covers mathematical and numerical methods for solving typical complex problems found in undergraduate-level physical chemistry courses. Topics include single variable integration, multivariate calculus, series and limits, ordinary and partial differential equations, determinants, matrices, vectors, and probability and statistics.

## Physical Chemistry I: Equillibrium Thermodynamics and Statistical Mechanics
<details>
<summary>Study material</summary>
<div markdown="1">
- ***Atkin's Physical Chemistry*** by Peter Atkins, Julio de Paula, and James Keeler
</div>
</details>
>The course consists of two parts. The first part teaches the equilibrium thermodynamics, covering the laws of thermodynamics and thermodynamics functions, with applications to various problems in phase equilibrium, chemical and electrochemical equilibrium. The second part teaches the equilibrium statistical thermodynamics, covering the Boltzmann distribution, the statistical ensembles and partition functions and their relations to thermodynamics functions.

## Great Ideas in Chemistry
>The course covers many major advances, historical developments and contemporary applications of critical concepts in Chemistry. These may range from atomic theory and identification and arrangement of the elements to modern problems such as CO2 and global warming; pollution and environmental clean-up. Unlike other Chemistry courses it will focus on the background to our knowledge, on what experimental evidence our current theories are based, and how old ones were overturned or modified.

## Chemistry in the Mass Media
>The public receives a lot of chemical information through mass media platforms (e.g. television, newspaper, social media, advertisements and products’ labelling), but occasionally these contain Chemistry depicted in a misleading or even pseudoscientific way. This experiential learning course aims to teach students to understand and apply the scientific method (observations, hypothesis, predictions, experiments, biases, etc.) through highly interactive lectures and a case study project based on a chosen social or daily life Chemistry topic from the mass media. Working in small groups, students will conduct both literature and experimental research on their chosen topic to evaluate its scientific claims and the public perception to them, under the instructor's supervision. Towards the end of the course, students will write up their findings into a scientific report for professional audience and construct a piece of science communication for laymen audience.

## Organic Chemistry II
>Dienes, resonance and aromaticity; electrophilic aromatic substitution and nucleophilic aromatic substitution; benzylic and allylic reactivity; the chemistry of carbonyl compounds and carboxylic acid derivatives; the chemistry of amines; pericyclic reactions.

## Inorganic Chemistry II
>Mechanism of inorganic reactions, organometallic and bioinorganic chemistry, catalysis.

## Instrumental Analysis
>Topics covered include electrochemistry, mass spectrometry and separation sciences.

## Physical Chemistry II
<details>
<summary>Study material</summary>
<div markdown="1">
- ***Atkin's Physical Chemistry*** by Peter Atkins, Julio de Paula, and James Keeler
</div>
</details>
>Basic quantum theory, atomic and molecular structure, equilibrium statistical thermodynamics.

## Structural Elucidation in Organic Chemistry
>Use of modern ID- and 2D-NMR, IR, and Mass Spectrometric techniques for structure determination of organic molecules; theory of each technique with emphasis on development of problem-solving techniques.

## Biomolecular Chemistry
>This course will introduce the fundamental chemical principles underlying the structure, properties, and functions of biologically important molecules. Using the chemical concepts of bonding, structure, and structure-reactivity relationships developed in organic chemistry, this course will cover topics on the stereochemistry, structural diversity, physicochemical properties, and reactivity of amino acids, peptides, proteins, nucleic acids, carbohydrates, and lipids to understand the molecular basis of their biological functions. Another major topic of this course is the preparation of these important biological molecules for understanding of their functions and exploitation of their biotechnological and medicinal values, using available organic chemistry methods.

## Medicinal Chemistry
>This course will introduce the chemistry principles underlying the drug-target interaction and the development of drugs. One of its major topics is the molecular basis of the interaction of medicinal compounds with various biomolecules and the effect of their structure on their therapeutic activities. In addition, this course will discuss the pharmacokinetics and pharmacodynamics properties of therapeutic agents and how these properties are related to their chemical structure. Moreover, another focus of this course is the chemical strategies to discover and optimize lead compounds that can eventually develop into agents of therapeutic values.

## Intermediate Organic Chemistry
>Provides further training in the multistep organic synthesis of natural and unnatural products, and will focus on the retrosynthetic analysis, control of stereochemistry, carbonyl group chemistry, and pericyclic reactions with a brief coverage on new synthetic methodologies for efficient synthesis of compound libraries. 

## Cheminformatics
>Basics of Chemometrics; Database mining (CSD and PDB); Multivariate data sets, statistics and data reduction; Data analysis and visualization; Molecular representation and chemical descriptors (e.g. SMILES / SMARTS patterns); Application to structure-based drug design.

## Solid State Chemistry
>Structure and bonding in solids; metals, semiconductors and dielectrics; crystal chemistry of ceramics, silicate minerals and zeolites; electrical, optical and magnetic properties of solids; fullerene chemistry; introduction to x-ray diffraction, electron microscopy, etc.

## Materials Chemistry
>An introduction of crystalline solids, crystal structures, materials synthesis and characterization techniques, optical characterization methods, semiconductors, optical, electrical and magnetic properties, and nanoscale inorganic materials.

## Materials Characterization Method
>This course will introduce a selected series of materials characterization methods with an emphasis on the characterization methods of nanomaterials, especially chemically processed nanomaterials. The characterization methods will include electron spectroscopies, electron microscopies, scanning probe microscopies, and optical, thermal, mechanical, scattering and diffraction methods. The course will provide a balanced mix of physical principles, application considerations, and practical examples of the characterization methods

## Intermediate Inorganic Chemistry
>Selected advanced topics in inorganic chemistry including spectroscopy (multinuclear NMR, IR and UV/visible), solid state chemistry, bioinorganic chemistry and catalysis.

## Environmental Chemistry
>Chemical phenomena in the hydrosphere, lithosphere and atmosphere; their interaction with the biosphere; origin and treatment of pollutants and hazardous waste; environmental monitoring and analysis.

## Environmental Analytical Chemistry
>Topics covered include fundamentals of sampling issues, sample pretreatment techniques, water Analysis of major and trace constituents; determination of inorganic and organic gas pollutants, Atmospheric analysis of particulate matter, determination of soil pollutants, environmental control standards, chemometrics in environmental analysis.

## Separation Science
>This course aims to provide an in-depth understanding of the working principles in separating substances by chemical and physical techniques. Topics in this course include: sample preparation for chromatographic analysis; instrumentation for gas and liquid chromatography; mass spectrometry, and etc. Applications of various separation techniques for forensic, environmental, biological, pharmaceutical, food and drink analyses are provided as illustrating examples.

## Bioanalytical Techniques
>Topics covered include fundamentals of optical microscopic techniques, protein analysis, enzymatic bioassays; DNA techniques and biomicrofluidic techniques.

## Physical Chemistry in Biological Applications
>This course covers the applications of physical chemistry in biological science and emphasizes the capability in using the fundamental knowledge in physical chemistry to solve the latest research problems in the interdisciplinary areas. Topics include molecular interpretations of the laws of thermodynamics, free energy and physical equilibria in membranes, photochemistry and photobiology, enzyme kinetics, binding and conformation transitions, spectroscopy of biomolecular structures and interactions.

## Statistical Machine Learning Methods for Chemical Data Analysis
>The basic knowledge of probability and statistics, chemical data preparation and visualization; numerical methods for chemical data analysis: regression, classification, feature selection and neural network.

## Symmetry in Chemistry and Spectroscopy
>Symmetry principle and group theory, molecular spectroscopy, advanced topics in molecular orbital theory and bonding, chemical kinetics.

## Organometallic Chemistry
>Bonding, structure and reactivity of organometallic compounds, ligand substitution, oxidative addition, reductive elimination reactions, insertions and reactions of coordinated ligands, applications to catalytic processes and organic synthesis.

## Chemistry for Advanced Solar Cell Technologies
>Solar Cells are considered as one of the most promising renewable energy technologies. Conventional solar cells are based on inorganic materials such as silicon. In the past decade, however, several new solar cell technologies based on organic materials are emerging as promising alternatives to conventional solar cells. This is an exciting and highly interdisciplinary area involving Chemistry, Physics, Materials Science, and Electronic Engineering. The study on organic solar cells provides an excellent platform for Science and Engineering students to learn about how to do research in a multidisciplinary environment.

## Modern Approaches to Biochemical and Cell Biological Research
>Our current understanding of biochemical reactions and internal organization of a cell was progressively enriched by technological and conceptual breakthroughs in the 20th century. This course will use personal and scientific stories of six prominent scientists to highlight research areas that are still being actively pursued today. Topics to include are DNA and protein biochemistry, physical and chemical methods for biological research, and the use of model organisms.

## Cell Biology
>Structure and function of the cell and sub-cellular organelles; from genes to proteins; membrane and cytoskeleton; cell communication and cell signaling; cell cycle and programmed cell death.

## Biodiversity
>This course introduces students to the diversity of life and habitats; the evolution and extinction of species; the values of biodiversity; challenges to the biodiversity and conservation approaches; the interrelationships between humans/biodiversity and the environment. Examples (local and global) and applications will be included to highlight the key concepts.

## Introduction to Biotechnology
>Advancement in science has enabled scientists to modify biological systems for specific purposes. Many of these technologies have been used to improve our daily life and this area of study is commonly referred to as biotechnology. This course is designed to introduce some of the major subjects in this field including the history of biotechnology, ethics in genetic modification and use of animals in experimental studies, molecular foundation of biotechnology, animal biotechnology, plant and agricultural biotechnology, and health-care applications. You will learn how different aspects of biotechnology affect our daily life and have impact on the society.

## Plant Biology
>Structure and life processes in plants; cellular structures; molecular and cellar mechanism; transport of water and nutrients; nutrition and soil; reproduction; photosynthesis; growth and development; biotechnology.

## Biochemistry I
>Major classes of biochemical compounds; primary, secondary, tertiary and quaternary structures of macromolecules; enzyme kinetics and mechanisms; biosynthesis of DNA and RNA; transfer RNA and protein synthesis.

## Biochemistry II
>Principles of bioenergetics and cellular structures; glycolysis, citric acid cycle, electron transport, oxidative phosphorylation and chemiosmosis; carbohydrate, lipid, amino acid and nucleotide metabolism; photosynthesis and nitrogen fixation.

## Molecular and Cellular Biology I
>Replication and roles of nucleic acids in cellular and viral systems; genome organization, vector-host systems, expression and regulation of genes; catalytic RNA, genetic code evolution, RNA modification and processing, and anti-sense systems.

## Molecular and Cellular Biology II
>Cell structure; the molecular biology of cell signaling and cell cycle control; oncogenes and tumor suppressor genes; the mechanism of cell division; cell junctions and adhesion; cytoskeleton; programmed cell death.

## Animal Physiology
>Structure and life processes in animals; neurophysiology; circulation; respiration; digestion and absorption; metabolism and energy regulation; muscle and movement; endocrinology.

## Microbiology
>Classification, identification, structure, physiology, and genetics of microorganisms; importance of microorganisms in health, environment, and biotechnology.

## Introduction to Biophysical Instrumentation
>The course offers an introduction to principles and applications of a variety of modern biophysical experimental techniques for the structural and functional study of biological systems at the cellular and molecular levels. It is designed for students who seek a basic understanding of modern biophysical experimental methods to meet future challenges in biological science, synthetic biology, biotechnology, bioengineering and molecular medicine.

## Biotechnological Application of Recombinant DNA Techniques
>Practical and theoretical consideration of recombinant DNA techniques, including plasmid construction, PCR, mutagenesis, transformation, sequencing, and bioinformatic analysis. The use of recombinant DNA for protein expression.

## General Genetics
>Principles and mechanisms of heredity and variation; genetic analysis in pro-and eukaryotic organisms.

## Biostatics
>Statistical reasoning relevant to biological, medical and agricultural research, statistical analyses and interpretation, statistical techniques applied under various research circumstances.

## Introduction to Neurobiology
>Principles of neuroscience with a focus on the systems/neural circuit level. Topics covered will include sensory and motor systems, genetic model organisms, optogenetics, and functional imaging.

## Bioinformatics
>An introduction to bioinformatic analysis in life science. Students will learn about the principles and approaches used in working with genetic, genomic and proteomic data. Applications to basic science and translational research will also be introduced. No experience in computer programing is required.

## Immunobiology
>Cellular, biochemical and genetic basis of immunity; cells in immune response, antigens and antigen recognition; antibodies and the generation of diversity; major histocompatibility complex; cell mediated immune response; regulation of immune response; autoimmunity, tissue transplantation and rejection.

## Developmental Biology
>Processes of cellular and tissue differentiation, early and late embryonic development spanning from molecular, cellular, organ to organismal levels; reproduction, fertilization, gastrulation, neurulation, axis formation, body patterning, cellular communication, short and long range signaling, sex determination, aging, environmental influence and evolutionary significance of different regulatory mechanisms.

## Cancer Biology
>Fundamentals in the epidemiology, etiology and treatment of cancers; basic mechanisms of carcinogenesis. 

## Cellular Signaling
>Recent advances in the study of the molecular mechanisms of cell function, with an emphasis on the structure and function of signaling components that control cell growth, differentiation, and integrated responses in eukaryotic cells.

## Data Science for Biology and Medicine
>This is a course for the application of data science in biology and medicine. The course will introduce the fundamental principles on data science, the technologies and implementations of data mining, as well as the modeling of several practical questions in biomedicine. The topics include introduction to biomedical data, data visualization, regression methods and classification methods.

## Human Genetics and Personalized Medicine
>Many variations in the human population such as hair thickness, tolerance to milk in adults, high blood cholesterol and susceptibility to certain types of cancer can be determined by genetic factors. This course will cover the principles and up to date technologies for the discovery and analysis of human genetic variation. The application of basic scientific knowledge in a clinical setting will be discussed.

## Structure and Function of Proteins
>Determination of protein sequences and three-dimensional structures; relationship between structure and function; principles of protein design and engineering; molecular, biochemical and genetic approaches to study protein function and regulation.

## Advanced Biological Chemistry
>Advanced studies of biological macromolecules; functional genomics and proteomics; laboratory techniques in modern biochemistry; milestone discoveries in biochemistry.

## Biochemistry of Diseases
>This course covers the clinical manifestations, physiology, pathophysiology and treatment of common human diseases, with focus on the underlying biochemical basis of the diseases and treatment.

## Epigenetics and Chromosome Biology
>Chromosome biology and epigenetics is an important field highly relevant to human health. This course will cover recent advances in the fields of epigenetics and chromosome biology.

## Neurochemistry
>Introduction to the molecular understanding of brain function, building upon the basis of biochemistry and biology. Four specific themes are covered: (i) structural neurochemistry and neural membranes; (ii) synapses, transmitters and receptors; (iii) cellular and (iv) medical and behavioral neurochemistry.

## Introductory Biological Physics
>This course introduces the use of physical methods in the study of biological systems, including macromolecules, membranes, nerves, muscle, photosynthetic systems and visual systems. The biological systems to which the methods are applied will be surveyed and current interpretations of their structure and function will be discussed. The treatment of biological phenomena will be based on physical principles with appropriate mathematics when necessary. The emphasis will be on the applications of physics in biology.

## Advanced Biological Physics
>Biological physics involves the application of physics to achieve an understanding of life processes. This is the second of a two-course series that will prepare advanced undergraduates for research and technical work in Biological physics. It covers advanced biological physics such as molecular and cellular biological physics, photophysics, single-molecule biophysics, medical biophysics, membrane biological physics, neurobiophysics, biostatistics, biomathematics, bioinformatics, computational biology and protein engineering. At the conclusion of this course, students will be able to critically assess primary research literature written for a general scientific audience. They will also be prepared for mentored practical research investigations or professional job related to biological physics.

## Principles of Quantitative Instrumentation
>This course aims to provide a general understanding of modern instruments used in biological research with special emphasis on bright-field and fluorescence light microscopes, electron microscopy, X-ray crystallography, NMR, MRI, mass spectrometer, and electrophysiology. The approach is a practical one geared to students who are or will be using these instruments in research. The course consists of both lectures and demonstration. During the lectures, students learn basic principles of biological instrumentation and the performance of the instruments. In the demonstration, students apply the understanding gained during the lectures and learn how the instrumentation is used to address biological questions.

## Programming with C++
<details>
<summary>Study material</summary>
<div markdown="1">
- ***Big C++: Late Objects*** by Cay Horstmann
</div>
</details>
>This course covers programming and data structures using C++. In addition to basic programming concepts such as variables and control statements, students will learn about arrays, pointers, dynamic data allocation, linked lists, stacks, queues, binary trees, recursion, and the basics of object oriented programming.

## Advanced Organic Chemistry I
>Mechanism and theory in organic chemistry, molecular orbital theory, structure-activity relationships, isotope effects, solvent effects, neighboring group participation, and reactive intermediates.

## Advanced Organic Chemistry II
>Stereochemistry and conformational analysis, reactions of various classes of organic compounds, synthetic organic chemistry, modern methods of synthesis including specific methodologies and multistep complex syntheses.

## Asymmetric Catalysis
>This course teaches the basic concepts and general modes of action of asymmetric catalysis and synthesis. Asymmetric catalysis is an essential tool in organic synthesis, which is used daily in various industries, such as pharmaceutical, chemical, agriculture, materials, etc. The course will provide in-depth explanation of how catalysts work in organic reactions and how asymmetric control is accomplished in different scenarios. Lectures will focus on mechanistic details of chirality control using case studies. Students are expected to be able to use this important tool to solve various synthetic problems.

## Advanced Medicinal Chemistry
>Drug design, structure-activity relations, chemistry and biological effects of major classes of physiologically active and psycho-active drugs.

## Computational Chemistry
>Fundamentals and applications of various computational chemistry methods, including molecular orbital calculations, molecular mechanics and molecular dynamics. Computational laboratory practice will be emphasized.

## Statistical Mechanics: Theory and Applications in Complex Systems
>Classical statistical mechanics and its applications in complex chemical and biological systems.

## Quantum Chemistry
<details>
<summary>Study material</summary>
<div markdown="1">
- ***Modern Quantum Chemistry*** by Attila Szabo and Neil S. Ostlund
</div>
</details>
>Introduction to basic theories of Quantum Chemistry. Popular theories used in modern Quantum Chemistry such as Hantree-Fock theory, Density Functional theory. Perturbation Theories, and other quantum chemistry theories will be introduced in this course.

## Advanced Inorganic Chemistry I
>Symmetry, group theory; molecular orbitals, electronic states; ligand field theory; electronic structure of metal complexes; theory of bonding and structure of inorganic compounds; chemistry of the elements; major physical methods used in the determination of molecular structure and bonding.

## Chemical X-ray Crystallography
>Applications of X-ray diffraction methods to the determination of crystal structures, including crystal symmetry, reciprocal lattice, intensity of diffraction, the phase problem, and refinement of structure parameters, powder X-ray diffraction analysis.

## Atmospheric Chemistry
>A fundamental introduction to the physical and chemical processes determining the composition of the atmosphere and its implications for climate, ecosystems, and human welfare. Atmospheric transport and transformation. Stratospheric ozone. Oxidizing power of the atmosphere. Regional air pollution: aerosols, smog, and acid rain. Nitrogen, oxygen, carbon, sulfur geochemical cycles. Climate and the greenhouse effect.

## Advanced Analytical Chemistry
>Various modalities of spectroscopy, spectrometry and microscopy, separation methods, probes and sensors, miniaturized analytical systems, environmental analysis and bioanalysis.

## Chemistry for Advanced Materials
>Chemistry of materials with nano-dimensional structures and advanced functionalities. Working principles of liquid-crystalline displays and organic light-emitting diodes. High-tech applications of luminescent materials in optoelectronic systems, chemical sensors and biological probes.

## Polymer Chemistry
>Modern Polymer synthesis, step and chain polymerizations, macromolecular structures, and polymer properties.



#### Reference

- https://prog-crs.hkust.edu.hk/ugcourse
- https://prog-crs.hkust.edu.hk/pgcourse
- http://stellar.mit.edu/index.html