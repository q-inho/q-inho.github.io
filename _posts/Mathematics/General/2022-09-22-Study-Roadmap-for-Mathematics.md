---
title:  "Study Roadmap for Mathematics"
excerpt: "Algebra, Number Theory, Analysis, Differential Equations, Geometry, Topology, Applied Mathematics, Financial Mathematics and others.."

categories:
  - math-general
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
        MATH24052 --> MATH5281
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

# Details
## Multivariable Calculus
<details>
<summary>Study material</summary>
<div markdown="1">
- *Textbook* by Author
</div>
</details>
>Sequences, series, gradients, chain rule. Extrema, Lagrange multipliers, line integrals, multiple integrals. Green's theorem, Stoke's theorem, divergence theorem, change of variables.



#### Reference

- https://prog-crs.hkust.edu.hk/ugcourse
- https://prog-crs.hkust.edu.hk/pgcourse
- http://stellar.mit.edu/index.html