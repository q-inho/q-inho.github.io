---
title:  "Study Roadmap for Finance"
excerpt: "Banking, Securities markets, Venture capital and private equity, Fintech and financial innovation, Green finance and others.."

categories:
  - General
tags:
  - [Finance]

toc: false
toc_sticky: false
 
date: 2022-09-25
last_modified_at: 2022-10-04
---

# My Roadmap for Finance

<div class="mermaid"> 
      graph LR
        subgraph Core Study
        ACCT2010[Principles of Accounting I]
        ACCT2200[Principles of Accounting II]
        ACCT3010[Financial Accounting I]
        ACCT3020[Financial Accounting II]

        ECON2113[Microeconomics]
        ECON3123[Macroeconomic Theory I]

        FINA2303[Financial Management]
        FINA3103[Intermediate Investments]
        FINA3203[Deviative Securities]
        FINA3303[Intermediate Corporate Finance]
        FINA3810[Bloomberg Market Concepts Certification]
        
        ISOM2010[Introduction to Information Systems]
        ISOM2020[Coding for Business]
        ISOM2500[Business Statistics]
        ISOM2600[Introduction to Business Analytics]
        ISOM2700[Operations Management]

        MGMT2010[Business Ethics and the Individual]
        MGMT2110[Oprganizational Behavior]
        MGMT2130[Business Ethics and Social Responsiblity]

        MARK2120[Marketing Management]
        end

        ACCT2010 --> ACCT2200
        ACCT2010 --> ACCT3010
        ACCT3010 --> ACCT3020
        ISOM2500 --> ISOM2600
        MGMT2010 --> MGMT2130


        subgraph Economics
        ECON2174[Mathematics for Economists]
        ECON3113[Microeconomic Theory I]
        ECON3133[Microeconomic Theory II]
        ECON3143[Macroeconomic Theory II]
        ECON3334[Introduction to Econometrics]
        ECON4114[Industrial Organization and Competitive Strategy]
        ECON4124[Applied Game Theory]
        ECON4134[Economics of Uncertainty and Information]
        ECON4234[Labor Economics and Human Resources]
        ECON4244[Economics of Human Behavior]
        ECON4254[Law and Economics]
        ECON4264[Economics of Innovation and Entreprenurship]
        ECON4274[Programming Econometrics with R]
        ECON4284[Econometrics for Cross-Section and Panel Data]
        ECON4334[Money and Banking]
        ECON4364[International Trade and Investment]
        ECON4374[International Macroeconomics and Finance]
        ECON4434[Economic Development and Growth]
        ECON4464[Urban and Environment Economics]
        ECON4474[Hong Kong's Economy]
        end



        ECON2113 --> ECON3113
        ECON3113 --> ECON3133
        ECON3113 & ECON3123 --> ECON3143
        ISOM2500 --> ECON3334
        ECON3113 & ECON3133 --> ECON4114
        ECON2113 --> ECON4124
        ECON3113 & ECON3133 --> ECON4134
        ECON3113 --> ECON4234
        ECON3113 & ECON3334 --> ECON4244
        ECON3133 --> ECON4254
        ECON2113 --> ECON4264
        ECON3334 --> ECON4274
        ECON3334 --> ECON4284
        ECON3113 & ECON3123 --> ECON4334
        ECON3113 & ECON3123 --> ECON4364
        ECON3113 & ECON3123 --> ECON4374
        ECON3133 --> ECON4434
        ECON2113 --> ECON4464
        ECON3113 & ECON3123 --> ECON4474


        subgraph Quantitative Finance
        ECON4304[Time Series Econometrics and Business Forecasting]

        FINA4803[Quantitative Trading]

        ISOM3230[Business Applications Programming]
        ISOM3360[Data Mining for Business Analytics]
        ISOM3370[Big Data Technologies]
        ISOM3540[Introduction to Probability Models]
        ISOM4520[Statistics for Financial Risk Management]
        ISOM4530[Statistical Analysis of Financial Data in R/S-plus]
        ISOM4540[Time Series Analysis and Forecasting]

        COMP2011[Programming with C++]
        COMP2012[Object-Oriented Programming and Data Structures]
        COMP3211[Fundamentals of Artificial Intelligence]
        COMP4211[Machine Learning]
        COMP4331[Data Mining]
        COMP4332[Big Data Mining and Management]
        COMP4471[Deep Learning in Computer Vision]

        MATH2023[Multivariable Calculus]
        MATH2121[Linear Algebra]
        MATH2352[Differential Equations]
        MATH2421[Probability]
        MATH3423[Statistical Inference]
        MATH4511[Quantitative Methods for Fixed Income Derivatives]
        MATH4512[Fundamentals of Mathematical Finance]
        end

        ECON3334 --> ECON4304
        ISOM2010 --> ISOM3230
        ISOM2010 & ISOM2020 --> ISOM3360
        ISOM3230 & ISOM3360 --> ISOM3370
        ISOM2500 --> ISOM3540
        ISOM3540 --> ISOM4520
        ISOM2500 --> ISOM4530
        ISOM2500 --> ISOM4540

        COMP2011 --> COMP2012
        COMP2011 --> COMP3211
        COMP2012 & ISOM2500 --> COMP4211
        ISOM2500 --> COMP4331
        ISOM3360 --> COMP4332
        COMP2011 & MATH2121 --> COMP4471

        MATH2421 --> MATH3423
        MATH2023 & MATH2121 & ISOM2500 & FINA2303 --> MATH4511
        MATH2023 & MATH2121 & ISOM2500 & FINA2303 --> MATH4512

        ACCT2010 & ISOM2500 --> FINA2303
        FINA2303 --> FINA3103
        FINA2303 --> FINA3203
        FINA2303 --> FINA3303
        FINA2303 --> FINA3820[Refinitiv Certification Program]
        FINA3103 --> FINA4003[Wealth Management]
        FINA3303 --> FINA4013[Corporate Valuation]
        FINA3103 --> FINA4103[Financial Markets Trading and Structure]
        FINA3303 --> FINA4203[Mergers, Acquisitions, and Corporate Restructing]
        FINA3103 & FINA3203 --> FINA4304[Fixed Income Securities]
        FINA3103 --> FINA4403[International Finance]
        FINA2303 --> FINA4413[Family Business]
        FINA2303 --> FINA4503[Banking and Financial Intermediation]
        FINA3103 & FINA3203 --> FINA4513[Risk Management]
        FINA3303 --> FINA4603[Venture Capital Financing]
        FINA3103 --> FINA4703[ESG Investing]


        subgraph Information Systems
        ISOM2030[Business Protections for Innovations]
        ISOM2040[Business Simulation and Strategic Decisions]
        ISOM2310[Fundamentals of E-Commerce: Business, Technology, and the Society]
        ISOM2400[Global Information Infrastructure and Policy]
        ISOM3010[Information Systems Project Management]
        ISOM3180[Telecommunications and Computer Networking Management]
        ISOM3210[Information Systems Analysis and Design]
        ISOM3260[Database Design and Administration]
        ISOM3310[e-Business Management and Web Analytics]
        ISOM3320[Internet Applications Development]
        ISOM3330[Data Visualization and Visual Analytics]
        ISOM3340[Developing AI Applications]
        ISOM3350[FinTech and Cryptoventures]
        ISOM3380[Advanced Network Management]
        ISOM3390[Business Programming in R]
        ISOM3400[Business Applications Development in Python]
        ISOM3530[Business Data Analytics]
        ISOM3710[Business Modeling and Optimization]
        ISOM3730[Quality and Process Management]
        ISOM3760[Logistics Management]
        ISOM3770[Global Supply Chain Management]
        ISOM3900[Decision Analytics]
        ISOM4010[Digital Business Strategy: Harnessing Platform, Crowd, and Machine]
        ISOM4020[Innovation Management and Technology Entreprenurship]
        ISOM4100[Information Systems Auditing]
        ISOM4200[Information and Cyber Security Management]
        ISOM4300[Information Systems Control and Assurance]
        ISOM4720[Simulation in Business and Management]
        ISOM4740[Enterprise Resource Management]
        ISOM4750[Business Project Management]
        ISOM4780[Integrated Planning and Execution]
        ISOM4830[Analytics for Service Operations]
        ISOM4840[Financial Service Operations Management]
        
        end

        ISOM2010 --> ISOM3210
        ISOM3230 --> ISOM3260
        ISOM2010 & ISOM2500 --> ISOM3350
        ISOM3180 --> ISOM3390
        ISOM3230 & ISOM3360 --> ISOM3390
        ISOM2020 --> ISOM3400
        ISOM2500 --> ISOM3530
        ISOM2700 --> ISOM3760
        ISOM2700 & ISOM3710 --> ISOM3770
        ISOM2500 & ISOM2700 --> ISOM3900
        ACCT2010 & ISOM2010 --> ISOM4100
        ISOM2010 --> ISOM4300
        ISOM2500 --> ISOM4720
        ISOM2700 --> ISOM4740
        ISOM2700 --> ISOM4750
        ISOM2700 --> ISOM4780
        ISOM2700 & ISOM3710 --> ISOM4830
        ISOM2500 & ISOM2700 --> ISOM4840

        subgraph Marketing
        MARK3220[Marketing Research]
        MARK3410[Promotion and Advertising Management]
        MARK3420[Consumer Behavior]
        MARK3430[Global Marketing]
        MARK3460[Retailing]
        MARK3470[Service Marketing]
        MARK3480[Pricing Strategy]
        MARK3510[Business to Business Marketing]
        MARK3520[Competitive Positioning]
        MARK3610[Digital Marketing]
        MARK3620[Marketing Analytics]
        MARK4210[Strategic Marketing]
        MARK4450[Brand Management]
        end

        MARK2120 --> MARK3220
        MARK2120 --> MARK3410
        MARK2120 --> MARK3420
        MARK2120 --> MARK3430
        MARK2120 --> MARK3460
        MARK2120 --> MARK3470
        MARK2120 --> MARK3480
        MARK2120 --> MARK3510
        MARK2120 --> MARK3520
        MARK2120 --> MARK3610
        MARK2120 & ISOM2500 --> MARK3620
        MARK3220 & MARK3420 --> MARK4210
        MARK2120 --> MARK4450

        subgraph Management
        MGMT3110[Human Resources Management]
        MGMT3120[Managerial Leadership]
        MGMT3130[Judgement and Decision Making in Organizations]
        MGMT3140[Negotiation]
        MGMT3160[Environmental Business Strategies]
        MGMT3170[Managing CSR]
        MGMT4210[Corporate Strategy]
        MGMT4220[Entrepreneurship and Innovation]
        MGMT4230[International Management]
        MGMT4240[Strategic Management in China]
        MGMT4250[Management Consulting]
        MGMT4270[Training and Development]
        MGMT4280[Transnational Legal Issues and Dispute Settlement]
        MGMT4290[HR Analytics]
        MGMT4300[Knowing and Managing Your Social Networs for Careers and Business]
        end

        MGMT2110 --> MGMT3110
        MGMT2110 --> MGMT3120
        MGMT2110 --> MGMT3130
        MGMT2110 --> MGMT3160
        MGMT2110 --> MGMT4210
        MGMT2110 --> MGMT4250
        MGMT3110 --> MGMT4270
        MGMT3110 --> MGMT4290
        MGMT2110 --> MGMT4300

        subgraph Risk Management and Business Intelligence
        RMBI3010[Data Analytics with R]
        RMBI3020[Practicing Risk Management using Case Studies]
        RMBI3110[Introduction to Risk Management and Business Intelligence]
        RMBI4110[Financial Service Operations Management]
        RMBI4210[Quantitative Methods for Risk Management]
        RMBI4220[Life Contingencies Models and Insurance Risk]
        RMBI4310[Advanced Data Mining for Risk Management and Business Intelligence]
        end

        RMBI3110 --> RMBI3010
        ISOM2500 --> RMBI3110
        ISOM2500 & ISOM2700 --> RMBI4110
        ISOM3540 --> RMBI4210
        ISOM3540 --> RMBI4220
        ISOM3360 --> RMBI4310


        subgraph Advanced Study
        FINA5110[Central Bank Operations]
        FINA5120[Corporate Finance]
        FINA5140[Advanced Topics in Financial Management]
        FINA5150[Corporate Risk Management]
        FINA5160[Private Equity Investing]
        FINA5200[Asset Management]
        FINA5210[Investment Analysis]
        FINA5220[Equity Investment Management]
        FINA5240[FinTech Analytics]
        FINA5250[Empirical Methods in Finance]
        FINA5260[FinTech: The Future of the Financial Industry]
        FINA5270[Portfolio Management with Fintech Applications]
        FINA5280[Smart Applications of Distributed Ledger Technology]
        FINA5290[Derivatives Analysis]
        FINA5300[Advanced Derivatives Analysis]
        FINA5330[Investment and Finance in China and Asia]
        FINA5350[Strategic Finance and Value Creation]
        FINA5360[Fixed Income Analysis]
        FINA5370[Equity Valuation]
        FINA5390[Venture Capital and Private Equity]
        FINA5410[Market Microstructure]
        FINA5440[Risk Management for Financial Institutions]
        FINA5450[Hedge Funds]
        FINA5480[Commodities, Trade Finance and Infrastructures]
        FINA5490[Advanced Venture Capital Investing]
        FINA5500[VC Entrepreneurships]
        FINA5510[Decision Making in Financial Institutions]
        FINA5520[Financial Data Analysis]
        FINA5530[Green Financec: Markets and Institutions]
        FINA5560[Structured Products and Exotic Options]
        FINA5590[Trading in Equity Markets]
        FINA5600[Real Estate Financing]
        FINA5620[Foreign Exchange Market]
        FINA5830[Statistical Methods for Risk Management]
        FINA5840[Financial Modeling]
        FINA5870[Big Data in Finance]

        ACCT5100[Financial Accounting Foundations]
        end

        ACCT3020 --> ACCT5100
        FINA3303 --> FINA5120
        FINA3103 --> FINA5210
        FINA5120 --> FINA5140
        FINA5120 & FINA5290 --> FINA5150
        FINA5210 --> FINA5220
        FINA5120 --> FINA5270
        FINA5120 --> FINA5290
        FINA5290 --> FINA5300
        FINA5120 --> FINA5330
        FINA5120 --> FINA5350
        FINA5210 --> FINA5360
        FINA5120 --> FINA5370
        FINA5120 --> FINA5390
        FINA5210 --> FINA5410
        FINA5120 --> FINA5440
        FINA5120 --> FINA5450
        FINA5120 & FINA5290 --> FINA5480
        FINA5210 & FINA5290 --> FINA5490
        FINA5120 --> FINA5500
        FINA5120 --> FINA5520
        FINA5120 & FINA5210 --> FINA5530
        FINA5300 --> FINA5560
        FINA5290 --> FINA5590
        ACCT5100 & FINA5120 --> FINA5600
        FINA5210 --> FINA5620
        FINA5210 --> FINA5830
        FINA5120 & FINA5210 & FINA5290 --> FINA5840
        FINA5240 --> FINA5870












</div>

---

# Undergraduate Finance
- Financial Management
- Intermediate Investments
- Derivative Securities
- Intermediate Corporate Finance
- Bloomberg Market Concepts Certification
- Refinitiv Certification Program
- Wealth Management
- Corporate Valuation
- Financial Markets Trading and Structure
- Mergers, Acquisitions, and Corporate Restructuring
- Fixed Income Securities
- International Finance
- Family Business
- Banking and Financial Intermediation
- Risk Management
- Venture Capital Financing
- ESG Investing
- Quantitative Trading

# Undergraduate Accounting
- Principles of Accounting I
- Principles of Accounting II
- Financial Accounting I
- Financial Accounting II

# Undergraduate Economics
- Microeconomics
- Mathematics for Economists
- Introductory Environmental and Health Economics
- Microeconomic Theory I
- Macroeconomic Theory I
- Microeconomic Theory II
- Macroeconomic Theory II
- Introduction to Econometrics
- Industrial Organization and Competitive Strategy
- Applied Game Theory
- Economics of Uncertainty and Information
- Labor Economics and Human Resources
- Economics of Human Behavior
- Law and Economics
- Economics of Innovtion and Entrepreneurship
- Programming Econometrics with R
- Econometrics for Cross-Section and Panel Data
- Time Series Econometrics and Business Forecasting
- Money and Banking
- International Trade and Investment
- International Macroeconomics and Finance
- Economic Development and Growth
- Urban and Environment Economics
- Hong Kong's Economy

# Undergraduate Information System
- Introduction to Information Systems
- Coding for Business
- Business Protections for Innovations
- Business Simulation and Strategic Decisions
- Fundamentals of E-Commerce: Business, Technology, and the Society
- Global Information Infrastructure and Policy
- Business Statistics
- Introduction to Business Analytics
- Operations Management
- Information Systems Project Management
- Telecommunications and Computer Networking Management
- Information Systems Analysis and Design
- Business Applications Programming
- Database Design and Administration
- e-Business Management and Web Analytics
- Internet Applications Development
- Data Visualization and Visual Analytics
- Developing AI Applications
- FinTech and Cryptoventures
- Data Mining for Business Analytics
- Big Data Technologies
- Advanced Network Management (CISCO - ICND)
- Business Programming in R
- Business Applications Development in Python
- Business Data Analytics
- Introduction to Probability Models
- Business Modeling and Optimization
- Quality and Process Management
- Logistics Management
- Global Supply Chain Management
- Decision Analytics
- Digital Business Strategy: Harnessing Platform, Crowd, and Machine
- Innovation Management and Technology Entrepreneurship
- Information Systems Auditing
- Information and Cyber Security Management
- Information Systems Control and Assurance
- Statistics for Financial Risk Management
- Statistical Analysis of Financial Data in R/S-plus
- Time Series Analysis and Forecasting
- Simulation in Business and Management
- Enterprise Resource Management
- Business Project Management
- Integrated Planning and Execution
- Analytics for Service Operations
- Financial Service Operations Management

# Undergraduate Management
- Business Ethics and the Individual
- Organizational Behavior
- Business Ethics and Social Responsiblity
- Human Resources Management
- Managerial Leadership
- Judgement and Decision Making in Organizations
- Negotiation
- Environmental Business Strategies
- Managing CSR (Corporate Social Responsibility)
- Corporate Strategy
- Entrepreneurship and Innovation
- International Management
- Strategic Management in China
- Management Consulting
- Training and Development
- Transnational Legal Issues and Dispute Settlement
- HR Analytics
- Knowing and Managing Your Social Networks for Careers and Business

# Undergraduate Marketing
- Marketing Management
- Marketing Research
- Promotion and Advertising Management
- Consumer Behavior
- Global Marketing
- Retailing
- Services Marketing
- Pricing Strategy
- Business to Business Marketing
- Competitive Positioning
- Digital Marketing
- Marketing Analytics
- Strategic Marketing
- Brand Management

# Undergraduate Risk Management and Business Intelligence
- Data Analytics with R
- Practicing Risk Management using Case Studies
- Introduction to Risk Management and Business Intelligence
- Financial Service Operations Management
- Quantitative Methods for Risk Management
- Life Contingencies Models and Insurance Risk
- Advanced Data Mining for Risk Management and Business Intelligence

# Undergraduate Computer Science
- Programming with C++
- Object-Oriented Programming and Data Structures
- Fundamentals of Artificial Intelligence
- Machine Learning
- Data Mining
- Big Data Mining and Management
- Deep Learning in Computer Vision

# Undergraduate Mathematics
- Multivariable Calculus
- Linear Algebra
- Differential Equations
- Probability
- Statistical Inference
- Quantitative Methods for Fixed Income Derivatives
- Fundamentals of Mathematical Finance

# Postgraduate Finance
- Financial Accounting Foundations
- Corporate Finance
- Central Bank Operations
- Advanced Topics in Financial Management
- Corporate Risk Management
- Private Equity Investing
- Asset Management
- Investment Analysis
- Equity Investment Management
- FinTech Analytics
- Empirical Methods in Finance
- FinTech: The Future of the Financial Industry
- Portfolio Management with Fintech Applications
- Smart Applications of Distributed Ledger Technology
- Derivatives Analysis
- Advanced Derivatives Analysis
- Investment and Finance in China and Asia
- Strategic Finance and Value Creation
- Fixed Income Analysis
- Equity Valuation
- Venture Capital and Private Equity
- Market Microstructure
- Risk Management for Financial Institutions
- Hedge Funds
- Commodities, Trade Finance and Infrastructures
- Advanced Venture Capital Investing
- VC Entrepreneurships
- Decision Making in Financial Institutions
- Financial Data Analysis
- Green Financec: Markets and Institutions
- Structured Products and Exotic Options
- Trading in Equity Markets
- Real Estate Financing
- Foreign Exchange Market
- Statistical Methods for Risk Management
- Financial Modeling
- Big Data in Finance

---

# Details
## Bloomberg Market Concepts Certification
<details>
<summary>Study material</summary>
<div markdown="1">
- [Bloomberg Certification](https://www.bloomberg.com/professional/product/bloomberg-market-concepts/)
</div>
</details>
>The course aims to provide students with knowledge of financial markets and Bloomberg functionality. The course consists of four modules: economic indicators, currencies, fixed income and equities. Students will need to complete all four modules to receive the Bloomberg Market Concepts certification. 

## Refinitiv Certification Program
<details>
<summary>Study material</summary>
<div markdown="1">
- [Refinitiv Academy](https://solutions.refinitiv.com/academy)
</div>
</details>
>This course will enable students to learn more about market information and the functionality of a Refinitiv data product most commonly used by financial professionals. It begins with the first module of basic overview and is followed by four core modules on data, screen design, graphics, analysis tools of various instruments, which includes one module of data retrieval in Excel.


#### Reference

- https://prog-crs.hkust.edu.hk/ugcourse
- https://prog-crs.hkust.edu.hk/pgcourse
- http://stellar.mit.edu/index.html