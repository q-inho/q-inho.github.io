---
title:  "Study Roadmap for Mathematics"
excerpt: "Algebra, Number Theory, Analysis, Differential Equations, Geometry, Topology, Applied Mathematics, Financial Mathematics and others.."

categories:
  - General
tags:
  - [Mathematics]

toc: false
toc_sticky: false
 
date: 2022-09-22
last_modified_at: 2022-09-23
---

# My Roadmap for Mathematics

<div class="mermaid"> 
      graph LR
        MATH2023[Multivariable Calculus]
        MATH2033[Mathematical Analysis]
        MATH2121[Linear Algebra]
        MATH2343[Discrete Structures]
        MATH2352[Differential Equations]
        MATH2411[Applied Statistics]
        MATH2421[Probability]
        MATH2511[Fundamentals of Actuarial Mathematics]
        MATH2741[Geometric Constructions]
        MATH2023 & MATH2033 & MATH2121 --> MATH3033[Real Analysis]
        MATH2121 --> MATH3121[Abstract Algebra]
        MATH2121 & MATH2033 --> MATH3312[Numerical Analysis]
        MATH2121 --> MATH3322[Matrix Computation]
        MATH2023 & MATH2121 --> MATH3332[Data Analytic Tools]
        MATH2121 & MATH2343 --> MATH3343[Combinatorial Analysis]
        MATH2421 --> MATH3423[Statistical Inference]
        MATH3423 --> MATH3424[Regression Analysis]
        MATH2421 --> MATH3425[Stochastic Modeling]
        MATH2411 --> MATH3426[Sampling]
        MATH2421 --> MATH3427[Bayesian Statistics]
        MATH2023 & MATH2033 --> MATH4023[Complex Analysis]
        MATH2023 & MATH2121 --> MATH4033[Calculus on Manifolds]
        MATH2352 & MATH3033 --> MATH4051[Theory of Ordinary Differential Equations]
        MATH2023 & MATH2121 & MATH2352 --> MATH4052[Partial Differential Equations]
        MATH3033 --> MATH4061[Topics in Modern Analysis]
        MATH4061 --> MATH4063[Functional Analysis]
        MATH3121 --> MATH4141[Number Theory and Applications]
        MATH2023 & MATH2121 --> MATH4151[Introduction to Lie Groups]
        MATH2033 & MATH2121 --> MATH4221[Euclidean and Non-Euclidean Geometries]
        MATH2023 & MATH2121 --> MATH4223[Differential Geometry]
        MATH2033 --> MATH4225[Topology]
        MATH2023 & MATH2121 --> MATH4321[Game Theory]
        MATH4052 --> MATH4326[Introduction to Fluid Dynamics]
        MATH2121 & MATH2352 --> MATH4333[Mathematical Biology]
        MATH2023 & MATH2121 --> MATH4335[Introduction to Optimization]
        MATH2023 & MATH2121 & MATH2352 --> MATH4336[Introduction to Mathematics of Image Processing]
        MATH2342 --> MATH4343[Introduction to Graph Theory]
        MATH2352 & MATH3312 & MATH4052 --> MATH4351[Numerical Solutions of Partial Differential Equations]
        MATH2411 --> MATH4423[Nonparametric Statistics]
        MATH3423 & MATH3424 --> MATH4424[Multivariate Analysis]
        MATH3423 & MATH3424 --> MATH4425[Introductory Time Series]
        MATH3423 --> MATH4426[Survival Analysis]
        MATH2421 & MATH2023 & MATH2511 --> MATH4427[Loss Models and their Applications]
        MATH3423 --> MATH4428[Bayesian Analysis and Credibility Theory]
        MATH2411 --> MATH4432[Statistical Machine Learning]
        MATH2023 & MATH2121 & MATH2411 & FINA2203[Fundamentals of Business Finance] --> MATH4511[Quantitative Methods for Fixed Income Derivatives]
        MATH2023 & MATH2121 & MATH2411 & FINA2203 --> MATH4512[Fundamentals of Mathematical Finance]
        MATH2421 --> MATH4513[Life Conttingencies Models and Insurance Risk]
        MATH2421 & MATH2511 --> MATH4514[Financial Economics in Actuarial Science]

        subgraph Advanced Study
        MATH5011[Advanced Real Analysis I]
        MATH5030[Complex Function Theory]
        MATH5111[Advanced Algebra I]
        MATH5112[Advanced Algebra II]
        MATH5143[Introduction to Lie Algebras]
        MATH5145[Lie Groups]
        MATH5230[Differential Topology]
        MATH5240[Algebraic Topology]
        MATH5251[Algebraic Geometry I]
        MATH5261[Algebraic Geometry II]
        MATH5281[Advanced Partial Differential Equations]
        MATH5285[Applied Analysis]
        MATH5311[Advanced Numerical Methods I]
        MATH5312[Advanced Numerical Methods II]
        MATH5350[Computational Fluid Dynamics for Inviscid Flows]
        MATH5351[Mathematical Methods in Science and Engineering I]
        MATH5352[Mathematical Methods in Science and Engineering II]
        MATH5353[Multiscale Modeling and Computational for Non-equilibrium Flows]
        MATH5380[Combinatorics]
        MATH5411[Advanced Probability Theory I]
        MATH5412[Advanced Probability Theory II]
        MATH5431[Advanced Mathematical Statistics I]
        MATH5432[Advanced Mathematical Statistics II]
        MATH5450[Stochastic Processes]
        MATH5460[Time Series Analysis]
        MATH5470[Advanced Statistical Machine Learning]
        MATH5471[Statistical Learning Models for Text and Graph Data]
        MATH5472[Computer Age Statistical Inference with Applications]
        MATH5473[Topological and Geometric Data Reduction and Visualization]
        MATH5520[Interest Rate Models]
        end

        MATH3033 --> MATH5011
        MATH3033 & MATH4023 --> MATH5030
        MATH3121 --> MATH5111
        MATH5111 --> MATH5112
        MATH3121 --> MATH5143
        MATH5111 & MATH5143 --> MATH5145
        MATH4225 --> MATH5230
        MATH5230 --> MATH5240
        MATH5111 --> MATH5251
        MATH5251 --> MATH5261
        MATH4052 --> MATH5281
        MATH2023 & MATH2121 & MATH2033 --> MATH5285
        MATH3312 --> MATH5311
        MATH5311 --> MATH5312
        MATH5351 --> MATH5352
        MATH5350 --> MATH5353
        MATH2342 & MATH3343 --> MATH5380
        MATH2421 --> MATH5411
        MATH5411 --> MATH5412
        MATH2411 --> MATH5431
        MATH5431 --> MATH5432
        MATH3425 --> MATH5450
        MATH4425 --> MATH5460
        MATH4432 --> MATH5470

        subgraph Computer Science Track
        COMP2011[Programming with C++]
        COMP2012[Object-Oriented Programming and Data Structures]
        COMP2611[Computer Organization]
        COMP3711[Design and Analysis of Algorithms]
        COMP3031[Principles of Programming Languages]
        COMP3111[Software Engineering]
        COMP3211[Fundamentals of Artificial Intelligence]
        COMP3311[Database Management Systems]
        COMP3511[Operating Systems]
        end

        COMP2011 --> COMP2012
        COMP2011 --> COMP2611
        COMP2011 & MATH2343 --> COMP3711
        COMP2012 --> COMP3031
        COMP2012 --> COMP3111
        COMP2011 --> COMP3211
        COMP2011 --> COMP3311
        COMP2611 --> COMP3511

        subgraph Mathematics and Physics Track
        PHYS2022[Modern Physics]
        PHYS3032[Classical Mechanics]
        PHYS3033[Electricity and Magnetism I,II]
        PHYS3036[Quantum Mechanics I]
        PHYS4051[Quantum Mechanics II]
        PHYS4050[Thermodynamics and Statistical Physics]
        end

        MATH2023 --> PHYS3033
        PHYS2022 --> PHYS3036
        PHYS3036 --> PHYS4051
        PHYS2022 --> PHYS4050

        subgraph Data Science and Technology
        COMP3632[Principles of Cybersecurity]
        COMP4021[Internet Computing]
        COMP4211[Machine Learning]
        COMP4221[Introduction to Natural Language Processing]
        COMP4222[Machine Learning with Structured Data]
        COMP4331[Data Mining]
        COMP4332[Big Data Mining and Management]
        COMP4421[Image Processing]
        COMP4631[Computer and Communication Security]
        COMP4641[Social Information Network Analysis and Engineering]
        COMP4651[Cloud Computing and Big Data Systems]
        end

        COMP2012 --> COMP3632
        COMP2012 --> COMP4021
        COMP2012 & MATH2411 --> COMP4211
        MATH2411 --> COMP4221
        COMP2011 & MATH2343 & MATH2121 --> COMP4222
        MATH2411 --> COMP4331
        COMP4331 --> COMP4332
        COMP2011 & MATH2352 --> COMP4421
        COMP3711 --> COMP4631
        COMP2011 & MATH2411 --> COMP4641
        COMP2011 --> COMP4651

        subgraph Mathematics and Economics
        ECON2113[Microeconomics]
        ECON3113[Microeconomic Theory I]
        ECON3123[Macroeconomic Theory I]
        ECON3133[Microeconomic Theory II]
        ECON3143[Macroeconomic Theory II]
        ECON3334[Introduction to Econometrics]
        ACCT2010[Principles of Accounting I]
        FINA2203[Fundamentals of Business Finance]
        end

        ECON2113 --> ECON3113
        ECON3113 --> ECON3133
        ECON3113 & ECON3123 --> ECON3143
        MATH2411 --> ECON3334






</div>

---

# Undergraduate Mathematics
- Multivariable Calculus
- Mathematical Analysis
- Linear Algebra
- Discrete Structures
- Differential Equations
- Applied Statistics
- Probability
- Fundamentals of Actuarial Mathematics
- Geometric Constructions
- Real Analysis
- Abstract Algebra
- Numerical Analysis
- Matrix Computation
- Data Analytic Tools
- Combinatorial Analysis
- Statistical Inference
- Regression Analysis
- Stochastic Modeling
- Sampling
- Bayesian Statistics
- Complex Analysis
- Calculus on Manifolds
- Theory of Ordinary Differential Equations
- Partial Differential Equations
- Topics in Modern Analysis
- Functional Analysis
- Number Theory and Applications
- Introduction to Lie Groups
- Euclidean and Non-Euclidean Geometries
- Differential Geometry
- Topology
- Game Theory
- Introduction to Fluid Dynamics
- Mathematical Biology
- Introduction to Optimization
- Introduction to Mathematics of Image Processing
- Introduction to Graph Theory
- Numerical Solutions of Partial Differential Equations
- Nonparametric Statistics
- Multivariate Analysis
- Introductory Time Series
- Survival Analysis
- Loss Models and their Applications
- Bayesian Analysis and Credibility Theory
- Statistical Machine Learning
- Quantitative Methods for Fixed Income Derivatives
- Fundamentals of Mathematical Finance
- Life Contingencies Models and Insurance Risk
- Financial Economics in Actuarial Science

# Undergraduate Computer Science
- Programming with C++
- Object-Oriented Programming and Data Structures
- Computer Organization
- Principles of Programming Languages
- Software Engineering
- Fundamentals of Artificial Intelligence
- Database Management Systems
- Operating Systems
- Principles of Cybersecurity
- Design and Analysis of Algorithms
- Internet Computing
- Machine Learning
- Introduction to Natural Language Processing
- Machine Learning with Structured Data
- Data Mining
- Big Data Mining and Management
- Image Processing
- Computer and Communication Security
- Social Information Network Analysis and Engineering
- Cloud Computing and Big Data Systems

# Undergraduate Economics
- Principles of Accounting I
- Fundamentals of Business Finance
- Microeconomics
- Microeconomic Theory I
- Macroeconomic Theory I
- Microeconomic Theory II
- Macroeconomic Theory II
- Introduction to Econometrics

# Undergraduate Physics
- Modern Physics
- Classical Mechanics
- Electricity and Magnetism I, II
- Quantum Mechanics I
- Quantum Mechanics II
- Thermodynamics and Statistical Physics

# Postgraduate Mathematics
- Advanced Real Analysis I
- Complex Function Theory
- Advanced Algebra I
- Advanced Algebra II
- Introduction to Lie Algebras
- Lie Groups
- Differential Topology
- Algebraic Topology
- Algebraic Geometry I
- Algebraic Geometry II
- Advanced Partial Differential Equations
- Applied Analysis
- Advanced Numerical Methods I
- Advanced Numerical Methods II
- Computational Fluid Dynamics for Inviscid Flows
- Mathematical Methods in Science and Engineering I
- Mathematical Methods in Science and Engineering II
- Multiscale Modeling and Computation for Non-equilibrium Flows
- Combinatorics
- Advanced Probability Theory I
- Advanced Probability Theory II
- Advanced Mathematical Statistics I
- Advanced Mathematical Statistics II
- Stochastic Processes
- Time Series Analysis
- Advanced Statistical Machine Learning
- Statistical Learning Models for Text and Graph Data
- Computer Age Statistical Inference with Applications
- Topological and Geometric Data Reduction and Visualization
- Interest Rate Models

---

# Details
## Multivariable Calculus
<details>
<summary>Study material</summary>
<div markdown="1">
- *Textbook* by Author
</div>
</details>
>Sequences, series, gradients, chain rule. Extrema, Lagrange multipliers, line integrals, multiple integrals. Green's theorem, Stoke's theorem, divergence theorem, change of variables.

## Mathematical Analysis
>Sets and functions, real numbers, limits of sequences and series, limits of functions, continuous functions, differentiation, Riemann integration, additional topics.

## Linear Algebra
>Vector space, matrices and system of linear equations, linear mappings and matrix forms, inner product, orthogonality, eigenvalues and eigenvectors, symmetric matrix.

## Discrete Structures
>Logic: propositions, axiomatization of propositional calculus, deduction theorem, completeness and soundness. Combinatorics: permutations and combinations, generating functions. Set theory: basic operations on sets, relations, countable and uncountable sets. Third year and fourth year students require instructor's approval to take the course.

## Differential Equations
>First and second order differential equations, initial value problems, series solutions, Laplace transform, numerical methods, boundary value problems, eigenvalues and eigenfunctions, Sturm-Liouville theory.

## Applied Statistics
>A systematic introduction to statistical inference, including the necessary probabilistic background, point and interval estimation, hypothesis testing.

## Probability
>Sample spaces, conditional probability, random variables, independence, discrete and continuous distributions, expectation, correlation, moment generating function, distributions of function of random variables, law of large numbers and limit theorems.

## Fundamentals of Actuarial Mathematics
>This course covers the fundamental concepts of actuarial financial mathematics and how these concepts are applied in calculating present and accumulated values for various streams of cash flows. The topics covered include interest rates, present value, annuities valuation, loan repayment, bond and portfolio yield, bond valuation, rate of return, yield curve, term structure of interest rates, duration and convexity of general cash flows and portfolios, immunization, stock valuation, capital budgeting, dynamic cash flow processes, and asset and liability management.

## Geometric Constructions
>This course is intended for students with some mathematical maturity. This course teaches geometric constructions using tools like straightedge and compass. Moreover, geometric constructions will be associated with algebraic fields of numbers and hence related to various famous constructability problems. Topics covered by the course include Euclidean constructions, compass-only constructions, straightedge-only constructions, constructability, three classical problems and regular polygons.

## Real Analysis
>Functions of several variables, implicit and inverse function theorem, uniform convergence measure and integral on the real line.

## Abstract Algebra
>Polynomials; Jordan canonical form, minimal polynomials, rational canonical form; equivalence relation; group, coset, group action; introduction to rings and fields.

## Numerical Analysis
>Basic numerical analysis, including stability of computation, linear systems, eigenvalues and eigenvectors, nonlinear equations, interpolation and approximation, numerical integration and solution of ordinary differential equations, optimization.

## Matrix Computation
>This course will introduce some basic matrix analysis theory and some popular matrix computation algorithms, and illustrate how they are actually used in data science. Specific topics include advanced linear algebra such as orthogonal projections and vector and matrix norms; the theories and computations of matrix factorizations such as QR decomposition, Singular Value Decomposition (SVD), and Schur decomposition; and applications to data analysis problems such as principle component analysis via SVD and collaborative filtering via matrix completion.

## Data Analytic Tools
>This course will introduce to the students some mathematical analysis tools that are useful for data analysis. The topics include Fourier analysis, wavelet analysis, function expansions, and basic functional analysis (Banach space, Hilbert spaces, linear operators, contract mapping, etc), and basic convex analysis (subgradient, convex conjugate).

## Combinatorial Analysis
>An introduction to combinatorics: What is combinatorics? Permutations and combinations, binomial theorem, generating permutations and combinations, pigeonhole principle, Ramsey theory, inclusion-exclusion principle, rook polynomials, linear recurrence relations, nonhomogeneous linear recurrence relations of the first and second order, generating functions, Catalan numbers, Stirling numbers, partition numbers, matchings and stable matchings, systems of distinctive representatives, block designs, Steiner triple systems, Latin squares, Burnside's lemma, Polya counting formula.

## Statistical Inference
>Sampling theory, order statistics, limiting distributions, point estimation, confidence intervals, hypothesis testing, non-parametric methods.

## Regression Analysis
>Estimation and hypothesis testing in linear regression, residual analysis, multicollinearity, indicator variables, variable selection, nonlinear regression.

## Stochasit Modeling
>Discrete time Markov chains and the Poisson processes. Additional topics include birth and death process, elementary renewal process and continuous-time Markov chains.

## Sampling
>Basic and standard sampling design and estimation methods. Particular attention given to variance estimation in sampling procedures. Topics include: simple random sampling, unequal probability sampling, stratified sampling, ratio and subpopulation and multistage designs.

## Bayesian Statistics
>This course provides a basic training of Bayesian statistics. Some ideas and principles of Bayesian including prior and posterior distributions, conjugate priors, Bayesian estimates, empirical Bayes, Bayesian hypothesis testing, Bayesian model selection and Bayesian networking are covered. Other Bayesian tools such as Bayesian decision theory, Bayesian data analysis, and Bayesian computational skills will also be discussed. An open-source, freely available software R will be used to implement these computational and data analytics skills. Hands-on experience and case studies such as pattern recognition and spam filtering will also be provided to students. Completion of this course will give students access to a wide range of Bayesian analytical tools, customizable to real data.

## Complex Analysis
>Complex differentiability; Cauchy-Riemann equations; contour integrals, Cauchy theory and consequences; power series representation; isolated singularities and Laurent series; residue theorem; conformal mappings.

## Calculus on Manifolds
>Introduction to manifolds, metric spaces, multi-linear Algebra, differential forms, Stokes theorem on manifolds, cohomology.

## Theory of Ordinary Differential Equations
>Existence and uniqueness theorems of ordinary differential equations, theory of linear systems, stability theory, study of singularities, boundary value problems.

## Partial Differential Equations
>Derivations of the Laplace equations, the wave equations and diffusion equation; Methods to solve equations: separation of variables, Fourier series and integrals and characteristics; maximum principles, Green's functions.

## Topics in Modern Analysis
>Examples and properties of metric spaces. Contractive mapping theorem, Baire category theorem, Stone-Weierstrass theorem, Arzela-Ascoli theorem. Properties of normed spaces and Hibert spaces. Riesz theorem. Completeness of Lp functions, continuous functions and functions of bounded variations. Best approximation theorem on Hilbert space.

## Functional Analysis
>Topological vector spaces. Hahn-Banach theorem, open mapping theorem, closed graph theorem, uniform boundedness theorem, separation theorem, Krein-Milman theorem. Weak topologies and reflexivity. Adjoints and duality. Compact and Fredholm operators with index. Normal operators. Spectral theorem for compact normal operators.

## Number Theory and Applications
>Prime numbers, unique factorization, modular arithmetic, quadratic number fields, finite fields, p-adic numbers, coding theory, computational complexity.

## Introduction to Lie Groups
>General linear groups, orthogonal groups, unitary groups, symplectic groups, exponential maps, maximal tori, Clifford algebra, spin groups.

## Euclidean and Non-Euclidean Geometries
>Axioms and models, Euclidean geometry, Hilbert axioms, neutral (absolute) geometry, hyperbolic geometry, Poincare model, independence of parallel postulate.

## Differential Geometry
>Curve theory; curvature and torsion, Frenet-Serret frame; surface theory: Weingarten map, first and second fundamental forms, curvatures, Gaussian map, ruled surface, minimal surface; instrinsic geometry: Theorema Egregium, Coddazi-Mainardi equations, parallel transport, geodesics, exponential map, Gauss-Bonnet theorem.

## Topology
>Metric, topology, continuous map, Hausdorff, connected, compact, graph, Euler number, CW-complex, classification of surfaces.

## Game Theory
>Zero-sum games; minimax theorem; games in extensive form; strategic equilibrium; bi-matrix games; repeated Prisonner's Dilemma; evolutionary stable strategies; games in coalition form; core; Shapley Value; Power Index; two-side matching games.

## Introduction to Fluid Dynamics
>Lagrangian and Eulerian methods for the flow description; derivation of the Euler and Navier-Stokes equations; sound wave and Mach number; 2D irrotational flow; elements of aerofoil theory; water wave dispersion relation; shallow water waves; ship wave pattern; dynamics of real fluid, stokes flow and boundary layer theory.

## Mathematical Biology
>Population, ecology, infectious disease, genetic, and biochemistry models. Additional topics chosen by instructor.

## Introduction to Optimization
>This course introduces fundamental theory and techniques of optimization. Topics include linear programming, unconstrained optimization, and constrained optimization. Numerical implementations of optimization methods are also discussed.

## Introduction to Mathematics of Image Processing
>This course introduces digital image processing principles and concepts, tools, and techniques with emphasis on their mathematical foundations. Key topics include image representation, image geometry, image transforms, image enhancement, restoration and segmentation, descriptors, and morphology. The course also discusses the implementation of these algorithms using image processing software.

## Introduction to Graph Theory
>This course is to equip students with basic knowledge of graph theory that will be needed in mathematics, computer science, and engineering (in particular network analysis). Topics include but not restricted to: Euler tours and Chinese postman problem, Hamilton cycles and traveling salesman problem; minimum spanning trees and searching algorithms; block decomposition, ear decomposition, connectivity and edge connectivity; network flows, Ford‐Fulkerson (Max‐Flow Min‐Cut) theorem, augmenting‐path algorithm; planar graphs, Euler formula, duality, classification of Platonic solids, Kuratowski (planarity) theorem; maximum matchings and perfect matchings, matchings in bipartite graphs, matchings in general graphs, Tutte‐Berge theorem, Petersen theorem; probabilistic method, page rank problem, random walks; cycle spaces and bond spaces, graph Laplace operator, matrix‐tree theorem; Four‐Color problem, colorings and flows, chromatic number and flow number, chromatic polynomials, flow polynomials, Tutte polynomials; matroids.

## Numerical Solutions of Partial Differential Equations
>Introduction to finite difference and finite element methods for the solution of elliptic, parabolic and hyperbolic partial differential equations; including the use of computer software for the solution of differential equations.

## Nonparametric Statistics
>The sign test; Wilcoxon signed rank test; Wilcoxon rank-sum test; Kruskal-Wallis test; rank correlation; order statistics; robust estimates; Kolmogorov-Smirnov test; nonparametric curve estimation.

## Multivariate Analysis
>Inferences of means and covariance matrices, canonical correlation, discriminant analysis, multivariate ANOVA, principal components analysis, factor analysis.

## Introductory Time Series
>Stationarity, (partial) auto-correlation function, ARIMA modeling, order selection, diagnostic, forecasting, spectral analysis.

## Survival Analysis
>The topics discussed in this course include basic quantities like hazard rate function, survival function, censoring and/or truncation; parametric estimation of the survival distribution by maximum likelihood estimation method; nonparametric estimation of the survival functions from possibly censored samples; parametric regression models; Cox's semi-parametric proportional hazards regression model; and multivariate survival analysis.

## Loss Models and their Applications
>This course covers the construction of casualty loss models and their applications to insurance. Topics include severity models, frequency models, aggregate loss models, coverage modifications, effect of inflation on losses, risk measures, parameter and variance estimation in loss models, and construction of empirical models.

## Bayesian Analysis and Credibility Theory
>This course provides a rigorous mathematical treatment of Bayesian analysis and its applications to credibility theory. The first part covers basic concepts and principles of Bayesian statistics such as prior and posterior distributions, conjugate priors, Bayesian estimates, credibility intervals, and Bayesian hypothesis testing. The second part introduces credibility theory and its development using a Bayesian analysis. Topics include limited fluctuation credibility theory, greatest accuracy credibility theory, credibility premium, Buhlmann models, Buhlmann-Straub models, empirical Bayesian methods in nonparametric and semiparametric cases, and the insurance problem.

## Statistical Machine Learning
>This course provides students with an extensive exposure to the elements of statistical machine learning in supervised and unsupervised learning with real world datasets. Topics include regression, classification, resampling methods, model assessment, model selection, regularization, nonparametric models, boosting, ensemble methods, random forests, kernel methods, support vector machines, neural networks, and some standard techniques in unsupervised learning such as clustering and dimensionally reduction. Lab sessions on using R or Python in data analysis with machine learning methods will be conducted in class.

## Quantitative Methods for Fixed Income Derivatives
>Bond, bond markets and interest-rate derivatives markets. Yields, forward rate and swap rates. Yield-based risk management and regression-based hedging. Mortgage mathematics. Binomial models for equity and fixed-income derivatives. Arbitrage pricing and risk-neutral valuation principle. Eurodollar futures. Lognormal models and Black formula for caps and swaptions.

## Fundamentals of Mathematical Finance
>Duration and horizon rate of return, bond portfolio management and immunization; mean-variance formulation of portfolio choices of risky assets; Two-fund theorem and One-fund theorem; asset pricing under the capital asset pricing models and factor models; investment performance analysis; utility optimization in investment decisions; stochastic dominance.

## Life Contingencies Models and Insurance Risk
>The topics discussed in this course include survival models, life tables and selection, insurance benefits, annuities, premium calculation, and insurance policy values.

## Financial Economics in Actuarial Science
>The course aims to study some actuarial models and their applications in derivative pricing and financial risk management. Topics include introduction to various derivatives such as forward, futures, European/ American options, exotic options and interest rate derivatives, uses of various options strategies in portfolio management, pricing options using binomial tree model, Black Scholes formula for options pricing and its extension, Options Greeks and their applications in hedging, use of Monte Carlo simulation in options pricing, pricing of interest rate derivatives using the Black-Derman-Toy tree. The course also prepares students to take the Exam MFE (Models for Financial Economics) of the Society of Actuaries.

## Programming with C++
>This course covers programming and data structures using C++. In addition to basic programming concepts such as variables and control statements, students will learn about arrays, pointers, dynamic data allocation, linked lists, stacks, queues, binary trees, recursion, and the basics of object oriented programming.

## Object-Oriented Programming and Data Structures
>To learn the fundamental concepts and techniques behind object-oriented programming. They include: abstract data types; creation, initialization, and destruction of objects; class hierarchies; polymorphism, inheritance and dynamic binding; generic programming using templates. To learn the object-oriented view of data structures: linked lists, stacks, queues, binary trees, and algorithms such as searching and hashing.

## Computer Organization
>Inner workings of modern digital computer systems and tradeoffs at the hardware-software interface. Topics include: instructions set design, memory systems, input-output systems, interrupts and exceptions, pipelining, performance and cost analysis, assembly language programming, and a survey of advanced architectures.

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

## Internet Computing
>Technologies and standards for World Wide Web (WWW), user interfaces and Browsers, authoring tools, Internet protocols, Internet servers, database connectivity, Robots, Search engines, server-side programming, client-side programming, security and privacy, recent advances.

## Machine Learning
>Fundamentals of machine learning. Concept learning. Evaluating hypotheses. Supervised learning, unsupervised learning and reinforcement learning. Bayesian learning. Ensemble Methods. Deep learning.

## Introduction to Natural Language Processing
>Human language technology for text and spoken language. Machine learning, syntactic parsing, semantic interpretation, and context-based approaches to machine translation, text mining, and web search.

## Machine Learning with Structured Data
>This course provides an introduction to statistical machine learning algorithms for structured data such as text sequences, taxonomy trees, relational databases (such as knowledge bases), and graphs (including graph databases such as biomedical graphs and large heterogeneous information networks such as knowledge graphs), and using programming tools such as Python to implement them for real problems. It will use some of the following practical problems such as text and graph classification, statistical relational learning, information extraction, sequence modeling, graph modeling, protein 3D structure prediction, QA system, etc. as illustrations to demonstrate the power of the statistical learning algorithms.

## Data Mining
>This course will provide an introduction to concepts and techniques in the field of data mining. Materials include an introduction to data warehousing and OLAP, data preprocessing and the techniques used to explore the large quantities of data for the discovery of predictive models and knowledge. The course will include techniques such as nearest neighbor, decision tress, neural networks, Bayesian networks and Naive Bayes, rule-based methods, association analysis and clustering, as well as social networks and data mining applications in business and finance applications, and other emerging data mining subareas. Students learn the materials by attending lectures and implementing and applying different data analysis and mining techniques to large datasets throughout the semester.

## Big Data Mining and Management
>This course will expose students to new and practical issues of real world mining and managing big data. Data mining and management is to effectively support storage, retrieval, and extracting implicit, previously unknown, and potentially useful knowledge from data. This course will place emphasis on two parts. The first part is big data issues such as mining and managing on distributed data, sampling on big data and using some cloud computing techniques on big data. The second part is applications of the techniques learnt on areas such as business intelligence, science and engineering, which aims to uncover facts and patterns in large volumes of data for decision support. This course builds on basic knowledge gained in the introductory data-mining course, and explores how to more effectively mine and manage large volumes of real-world data and to tap into large quantities of data. Working on real world data sets, students will experience all steps of a data-mining and management project, beginning with problem definition and data selection, and continuing through data management, data exploration, data transformation, sampling, portioning, modeling, and assessment.

## Image Processing
>Introduction to image processing. Topics include image processing and analysis in spatial and frequency domains, image restoration and compression, image segmentation and registration, morphological image processing, representation and description, object recognition, related application areas and some other closely related topics. Some sophisticated image processing and analysis tools and state-of-the-art methods may also be introduced subject to the availability of time.

## Computer and Communication Security
>Cryptosystems, symmetric-key and public-key cryptography, cryptanalysis, authentication, message digests, digital signatures, and random number generation. Access controls and firewalls. Applications such as certificate authorities, electronic commerce, smartcards, and digital cash.

## Social Information Network Analysis and Engineering
>This course is an introduction to social information network analysis and engineering. Students will learn both mathematical and programming knowledge for analyzing the structures and dynamics of typical social information networks (e.g. Facebook, Twitter, and MSN). They will also learn how social metrics can be used to improve computer system design as people are the networks. It will cover topics such as small world phenomenon; contagion, tipping and influence in networks; models of network formation and evolution; the web graph and PageRank; social graphs and community detection; measuring centrality; greedy routing and navigations in networks; introduction to game theory and strategic behavior; social engineering; and principles of computer system design. Students who do not have the prerequisites but with equivalent background may seek approval from the instructor for enrollment in the course.

## Cloud Computing and Big Data Systems
>Big data systems, including Cloud Computing and parallel data processing frameworks, emerge as enabling technologies in managing and mining the massive amount of data across hundreds or even thousands of commodity servers in datacenters. This course exposes students to both the theory and hands-on experience of this new technology. The course will cover the following topics. (1) Basic concepts of Cloud Computing and production Cloud services; (2) MapReduce - the de facto datacenter-scale programming abstraction - and its open source implementation of Hadoop. (3) Apache Spark - a new generation parallel processing framework - and its infrastructure, programming model, cluster deployment, tuning and debugging, as well as a number of specialized data processing systems built on top of Spark. By walking through a number of hands-on labs and assignments, students are expected to gain first-hand experience programming on real world clusters in production datacenters.

## Principles of Accounting I
>This is the first course of the principles of accounting sequence. Introduction to the concepts and principles of financial accounting, including the analysis, recording, and reporting of business transactions and preparation of financial statements.

## Fundamentals of Business Finance
>This course provides an introduction to corporate finance for students who may not have background in accounting and business statistics. Topics include financial statement analysis, time value of money, bond and stock valuation, capital budgeting, risk and return concepts and cost of capital.

## Microeocnomics
>Theory of the firm in a free enterprise system; theory of consumer demand; market structures and resource allocation; selected topics on government regulation. Students with non-local qualifications should seek department’s or school’s approval for enrollment in the course.

## Microeconomic Theory I
>The course presents a detailed study of basic topics in microeconomics with a special emphasis on using a rigorous analytical and mathematical approach. The topics include demand theory, uncertainty, asymmetric information, general equilibrium, welfare economics, externality, and public good. Multivariate calculus will be extensively used. Exclusively for students of the BSc programs in Economics & Finance and in Mathematics & Economics.

## Macroeconomic Theory I
>This course will concentrate on introducing the basics terms of macroeconomics, business cycle analysis, money and inflation, current accounts, and exchange rates.

## Microeconomic Theory II
>This is the second course in the microeconomics sequence. Topics include production theory, firms' behavior under different market structures (perfect competition, monopoly, oligopoly), factor demand, and game theory. Emphases are placed on a rigorous analytical and mathematical approach, and multivariate calculus will be used extensively.

## Macroeconomic Theory II
>This course will focus on long-term economic growth and structural change, theoretical elements of intertemporal macroeconomics, government budgets and deficits.

## Introduction to Econometrics
>Topics on the use of statistical regression techniques in modeling and estimating economic and business relationships. Both theoretical and applied aspects are addressed.

## Modern Physics
>Introduction to relativity; introduction to quantum theory: particle-wave duality and Schrodinger equation; atoms, molecules; and statistical physics: Maxwell, Bose and Fermi distributions.

## Classical Mechanics
>Newtonian mechanics, including rigid bodies; oscillating systems; gravitation and planetary motion; Lagrange equations; Hamilton's equations; normal modes and small oscillations.

## Electricity and Magnetism I, II
>A physics core course. Electrostatics: electric charge and fields, multipoles, Laplace equation, dielectrics; magnetostatics: currents, magnetic fields and vector potential, magnetic materials; Maxwell's equations.

>Electrodynamics: applications of Maxwell's equations, propagation in various media, radiation, relativistic electrodynamics, transmission lines and wave guides.

## Quantum Mechanics I
>Basic properties of Schrodinger equation, bound and scattering states in simple one-dimensional potentials, formulation of quantum mechanics in terms of Hilbert space and Dirac bracket notation, Schrodinger equation in three-dimensions, angular momentum, hydrogen atom wavefunction, systems of identical particles, spin and statistics, multi-electron atoms and the periodic table.

## Quantum Mechanics II
>This course is mainly on approximation methods in quantum mechanics. Topics include stationary state perturbation theory, variational principle, WKB method, time-dependent perturbation theory, emission and absorption of radiation, adiabatic approximation and geometric phase, scattering theory.

## Thermodynamics and Statistical Physics
>Laws of thermodynamics, entropy, thermodynamic relations, free energy; elementary statistical mechanics: Maxwell-Boltzmann, Bose-Einstein and Fermi-Dirac statistics; elementary transport theory; applications to physical systems.

## Advanced Real Analysis I
>Basic topology, continuous function spaces, abstract measure and integration theory, Lp spaces, convexity and inequalities, Hilbert spaces, Banach spaces, Complex measure.

## Complex Function Theory
>Review of basic properties of analytic functions. Phragmen-Lindelof principle, normal family, Riemann mapping theorem. Weierstrass factorization theorem, Schwarz reflection principle, analytic continuation, harmonic function, entire function, Hadamard factorization theorem, Picard theorem.

## Advanced Algebra I
>Advanced theory of groups, linear algebra, rings, modules, and fields, including Galois theory.

## Advanced Algebra II
>Advanced topics in algebra: group representations, associative algebras, commutative algebra, homological algebra, algebraic number theory.

## Introduction to Lie Algebras
>Lie algebras. Nilpotent, solvable and semisimple Lie algebras. Universal enveloping algebras and PBW-theorem. Cartan subalgebras. Roots system, Weyl group, and Dynkin diagram. Classification of semisimple Lie algebras. Representations of semisimple algebras. Weyl character formula. Harish-Chandra isomorphism theorem.

## Lie Groups
>This course is an introduction to the structure and representation theory of compact and noncompact reductive Lie groups. Topics include general properties of Lie groups and Lie algebras, Peter-Weyl Theorems, representations of compact Lie groups, theorems of the highest weight, Harish-Chandra isomorphism, Weyl character formula, the structure theory of noncompact semisimple and reductive Lie groups, classification of simple real Lie algebras, induced representation and Frobenius reciprocity, classical branching theorems.

## Differential Topology
>Manifolds, embedding and immersion, Sard's theorem, transversality, degree, vector fields, Euler number, Euler-Poincare theorem, Morse functions.

## Algebraic Topology
>Fundamental group, covering space, Van Kampen theorem, (relative) homology, exact sequences of homology, Mayer-Vietoris sequence, excision theorem, Betti numbers and Euler characteristic.

## Algebraic Geometry I
>Projective spaces, algebraic curves, divisors, line bundles, algebraic varieties, coherent sheaves, schemes. Some commumative algebra and homological algebra such as notherian ring, regular ring, valuation ring, kahler differentials.

## Algebraic Geomtery II
>Derived functors, cohomology of coherent sheaves on schemes, extension groups of sheaves, higher direct image of sheaves, Serre duality, flat morphisms, smooth morphisms, and semi-continuity, basics of curves and surfaces.

## Advanced Partial Differential Equations
>This is an introductory postgraduate course on Partial Differential Equations (PDEs). We will start with the classical prototype linear PDEs, and introduce a variety of tools and methods. Then we will extend our beginning theories to general situation using the notion of Sobolev spaces, Holder space and weak solutions. We will prove the existence, uniqueness, regularity and other properties of weak solutions.

## Applied Analysis
>Contraction mapping theorem, Fourier series, Fourier transforms, Basics of Hilbert Space theory, Operator theory in Hilbert Spaces, Basics of Banach space theory, Convex analysis.

## Advanced Numerical Methods I
>Numerical solution of differential equations, finite difference method, finite element methods, spectral methods and boundary integral methods. Basic theory of convergence, stability and error estimates.

## Advanced Numerical Methods II
>Direct and iterative methods. Programming techniques and softwares libraries. Sparse solvers, Fast algorithms, multi-grid and domain decomposition techniques.

## Computational Fluid Dynamics for Inviscid Flows
>Derivation of the Navier-Strokes equations; the Euler equations; Lagriangian vs. Eulerian methods of description; nonlinear hyperbolic conservation laws; characteristics and Riemann invariants; classification of discontinuity; weak solutions and entropy condition; Riemann problem; CFL condition; Godunov method; artificial dissipation; TVD methods; and random choice method.

## Mathematical Methods in Science and Engineering I
>Modeling and analytical solution methods of nonlinear partial differential equations (PDEs). Topics include: derivation of conservation laws and constitutive equations, well-posedness, traveling wave solutions, method of characteristics, shocks and rarefaction solutions, weak solutions to hyperbolic equations, hyperbolic Systems, linear stability analysis, weakly nonlinear approximation, similarity methods, calculus of variations.

## Mathematical Methods in Science and Engineering II
>Asymptotic methods and perturbation theory for obtaining approximate analytical solutions to differential equations. Topics include: local analysis of solutions to differential equations, asymptotic expansion of integrals, global analysis and perturbation methods, WKB theory, multiple-scale analysis, homogenization method.

## Multiscale Modeling and Computation for Non-equilibrium Flows
>Introduction of the Navier-Strokes equations and the flow modeling in the hydrodynamic scale. The derivation of the Boltzmann equation in the kinetic scale. The basic mathematical analysis of the Chapman-Enskog expansion and the numerical methods for the Boltzmann equation. The multiscale modeling from the kinetic to the hydrodynamic scales and the discretized governing equations. The study of non-equilibrium transport phenomena in gas dynamics, radiative and heat transfer, and plasma physics.

## Combinatorics
>Enumerative Combinatorics: bijective counting, permutation statistics, generating functions, partially ordered sets, Mobius inversions, Polya theory. Graph Theory: cycle space, bond space, spanning-tree formulas, matching theory, chromatic polynomials, network flows. Matroid Theory: matroid axioms, representations, duality, lattice of flats, transversals.

## Advanced Probability Theory I
>Probability spaces and random variables, distribution functions, expectations and moments, independence, convergence concepts, law of large numbers and random series.

## Advanecd Probability Theory II
>Stable laws; infinitely divisible distributions; weak convergence on general metric spaces; Donsker’s invariance principle; basic martingale theory; optional stopping theorem; martingale convergence theorems; martingale CLT; Concentration inequalities; logarithmic Sobolev inequality; large deviation.

## Advanced Mathematical Statistics I
>Theory of statistical inference in estimation. Topics include: sufficiency, ancillary statistics, completeness, UMVU estimators, information inequality, efficiency, asymptotic maximum likelihood theory. Other topics may include Bayes estimation and conditional inference.

## Advanced Mathematical Statistics II
>Theory of statistical inference in hypothesis testing. Topics include: uniformly most powerful tests, unbiasedness, invariance, minimax principle, large-sample parametric significance tests. Concept of decision theory also covered.

## Stochastic Processes
>Theory of Markov processes, second order stationary theory, Poisson and point processes, Brownian motion, Martingales and queueing theory.

## Time Series Analysis
>Basic idea of time series analysis in both the time and frequency domains. Topics include: autocorrelation, partial ACF, Box and Jerkins ARIMA modeling, spectrum and periodogram, order selection, diagnostic and forecasting. Real life examples will be used throughout the course.

## Advanced Statistical Machine Learning
>This course covers methodology, major software tools and applications in statistical learning. By introducing principal ideas in statistical learning, the course will help students understand conceptual underpinnings of methods in data mining. The topics include regression, logistic regression, feature selection, model selection, basis expansions and regularization, model assessment and selection; additive models; graphical models, decision trees, boosting; support vector machines; clustering.

## Statistical Learning Models for Text and Graph Data
>This course covers methodology, major software tools and applications in statistical learning. By introducing principal ideas in statistical learning, the course will help students understand conceptual underpinnings of methods in data mining. The topics include regression, logistic regression, feature selection, model selection, basis expansions and regularization, model assessment and selection; additive models; graphical models, decision trees, boosting; support vector machines; clustering.

## Computer Age Statistical Inference with Applications
>This course is designed for RPg students in applied mathematics, statistics, and engineering who are interested in learning from data. It covers advanced topics in statistical learning and inference, with emphasis on the integration of statistical models and algorithms for statistical inference. This course aims to first make connections among classical topics, and then move forward to modern topics, including statistical view of deep learning. Various applications will be discussed, such as computer vision, human genetics, and text mining.

## Topological and Geometric Data Reduction and Visualization
>This course is a mathematical introduction to data analysis and visualization with a perspective of topology and geometry. Topics covered include: classical linear dimensionality reduction, the principal component analysis (PCA) and its dual multidimensional scaling (MDS), as well as extensions to manifold learning, topological data analysis, and sparse models in applied math/high dimensional statistics. Extensive application examples in biology, finance, and information technology are presented along with course projects.

## Interest Rate Models
>Theory of interest rates, yield curves, short rates, forward rates. Short rate models: Vasicek model and Cox-Ingersoll-Ross models. Term structure models: Hull-White fitting procedure. Heath-Jarrow-Morton pricing framework. LIBOR and swap market models, Brace-Gatarek-Musiela approach. Affine models.


#### Reference

- https://prog-crs.hkust.edu.hk/ugcourse
- https://prog-crs.hkust.edu.hk/pgcourse
- http://stellar.mit.edu/index.html