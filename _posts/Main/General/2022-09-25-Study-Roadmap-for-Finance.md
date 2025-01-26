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
last_modified_at: 2024-03-24
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
        MGMT2110[Organizational Behavior]
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
        FINA3103 --> FINA4713[Introduction to Artificial Intelligence and Big Data in Finance]


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
- Introduction to Artificial Intelligence and Big Data in Finance

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

## Undergraduate Finance
### Financial Management
<details>
<summary>Study material</summary>
<div markdown="1">
- ***Corporate Finance: Core Principles and Applications*** by Stephen A. Ross, Randolph W. Westerfield,  Jeffrey F.  Jaffe, and Bradford D.  Jordan
</div>
</details>
>This course provides an introduction to corporate finance. Topics include time value of money, bond and stock valuation, capital budgeting, risk and return concepts and cost of capital.


### Intermediate Investments
<details>
<summary>Study material</summary>
<div markdown="1">
- ***Investments*** by Z. Bodie, A. Kane, A.J. Marcus, and Ravi Jain 
</div>
</details>
>This course studies the concepts and evidence relevant to the management of investment portfolios. Topics include diversification, asset allocation, portfolio optimization, factor models, the relation between risk and return, trading, passive (e.g., index-fund) and active (e.g., hedge-fund, long-short) strategies, mutual funds, performance evaluation, long-horizon investing and simulation.

### Derivative Securities
<details>
<summary>Study material</summary>
<div markdown="1">
- ***Options, Futures, & Other Derivatives*** by John C. Hull
</div>
</details>
>This course covers options, forward contracts, futures contracts and swaps. By the end of this course, students will have a good knowledge of how derivative contracts work, how they are used and how they are priced.

### Intermediate Corporate Finance
<details>
<summary>Study material</summary>
<div markdown="1">
- ***Corporate Finance*** by Ross, Westerfield, Jaffe, and Jordan
</div>
</details>
>The course provides an in-depth treatment of long-term financing decisions, including estimation of the cost of capital, financial leverage, corporate distress, raising financing, dividend policy, and working capital analysis.


### Bloomberg Market Concepts Certification
<details>
<summary>Study material</summary>
<div markdown="1">
- [Bloomberg Certification](https://www.bloomberg.com/professional/product/bloomberg-market-concepts/)
</div>
</details>
>The course aims to provide students with knowledge of financial markets and Bloomberg functionality. The course consists of four modules: economic indicators, currencies, fixed income and equities. Students will need to complete all four modules to receive the Bloomberg Market Concepts certification. 

### Refinitiv Certification Program
<details>
<summary>Study material</summary>
<div markdown="1">
- [Refinitiv Academy](https://solutions.refinitiv.com/academy)
</div>
</details>
>This course will enable students to learn more about market information and the functionality of a Refinitiv data product most commonly used by financial professionals. It begins with the first module of basic overview and is followed by four core modules on data, screen design, graphics, analysis tools of various instruments, which includes one module of data retrieval in Excel.

### Wealth Management
<details>
<summary>Study material</summary>
<div markdown="1">
- ***Investments*** by Bodie, Kane and Marcus
- ***Investment Analysis and Portfolio Management*** by Reilly and Brown
- ***Financial Planning and Wealth Management: An International Perspective*** by Cheng, Leung and Wong
</div>
</details>
>This course focuses on a broad understanding of financial and investment issues arising in the context of personal wealth management. Students will gain an understanding of the nature and use of various financial products and legal instruments for developing a financial plan. It covers topics such as client financial status and expectations, portfolio management, securities trading, managed funds, insurance, and tax and estate planning.

### Corporate Valuation

>This course teaches students how to use financial information to value firms. By the end of this course, students will be able to value firms using discounted cash flow valuation, relative valuation, and real options.

### Financial Markets Trading and Structure
<details>
<summary>Study material</summary>
<div markdown="1">
- ***Information Choice in Macroeconomics and Finance*** by Veldkamp, Laura
- ***Empirical Market Microstructure*** by Hasbrouck, Joel
- ***Market Liquidity: Theory, Evidence, and Policy*** by Foucault, Thierry; Marco Pagano; and Ailsa Roell
- ***DeFi and the Future of Finance*** by Harvey, Campbell; Ashwin Ramachandran; Joey Santoro; Fred Ehrsam; and Vitalik Buterin
</div>
</details>
>This course examines liquidity, market structure and trading. The focus is on examining the efficiency of trading systems and markets, the impact of new algorithmic trading on markets, the role of intermediaries and regulatory actions on market structure issues. Students learn about a number of alternative market structures in terms of their economic and operational effectiveness.

### Mergers, Acquisitions, and Corporate Restructuring
<details>
<summary>Study material</summary>
<div markdown="1">
- ***Mergers, Acquisitions, and Other Restructuring Activities: An Integrated Approach to Process, Tools, Cases, and Solutions*** by Donald M. DePamphilis 
- ***Mergers, Acquisitions, and Corporate Restructurings*** by Patrick A. Gaughan
- ***Corporate Finance*** by Ross S, Westerfield RW, Jaffe J, Jordan B
</div>
</details>
>This course analyzes mechanisms underlying the creation of value in mergers, acquisitions and corporate restructuring. Students will learn analytical techniques and tools to analyze (a) strategy behind corporate restructuring transactions, whether and what to acquire, (b) evaluation and financing of acquisitions, and (c) decisions and processes that impact value creation in mergers.

### Fixed Income Securities
<details>
<summary>Study material</summary>
<div markdown="1">
- ***Fixed Income Analysis*** by CFA Institute
- ***Fixed Income Securities: Valuation. Risk and Risk Management*** by Veronesi
</div>
</details>
>Pricing of bonds, term structure models, duration analysis and immunization techniques, valuation of interest rate options, convertible bonds, mortgage-backed securities, pricing credit derivatives, bond portfolio construction and management.

### International Finance

>An introduction to the fundamental principles of international financial management and investment. Topics include: international financial markets and instruments; foreign exchange markets; foreign currency derivatives and currency risk; international capital budgeting; international bond and equity markets.

### Family Business

>This course aims to provide students with comprehensive and practical understanding of Asian family business, which is the most prominent and significant business form in Asia. The course will specifically cover valuation and ownership design, financing and exit strategies, governance and succession practices of family businesses. The course is application oriented and draws on the faculty’s research experience and active interactions with family businesses in Asia. This course will benefit not only the students who will work in family businesses but also those likely to provide services to them in the future, such as private and investment bankers, family office professionals, private equity professionals, and other service professionals working closely with wealthy families in the region.

### Banking and Financial Intermediation

>This course examines financial intermediaries with a particular emphasis on banks. It introduces students to the nature, purpose, and management of these institutions. The course also brings together the upstream issues in risk measurement and the regulative environment surrounding banks. By the end of this course, students will be able to understand the role of banks in the economy and the effects of frictions such as information asymmetry and agency costs on bank behavior. The course will start with the review of basic game theory.

### Risk Management

>This course covers the role of risk management in supporting companies as they strive to balance the internal and external risk factors surrounding the operation of their business model against their various stakeholder obligations. Topics include a review of basic hedging strategies (knowledge of futures and options is pre-requisite), the theory and evidence on the value of corporate risk management, review of major surveys of risk management practices, business-case studies highlighting advanced derivatives and risk-management strategies, an illustrative model of integrated enterprise risk- management (featuring Monte-Carlo simulation), and student-led risk-management audits.

### Venture Capital Financing
<details>
<summary>Study material</summary>
<div markdown="1">
- ***Corporate Finance*** by Ross S, Westerfield RW, Jaffe J, Jordan B
- ***International Private Equity and Venture Capital Valuation Guidelines*** by *IPEV
- ***Venture Capital, Private Equity, and the Financing of Entrepreneurship*** by Lerner, J, Leamon, A & Hardymon, F
- ***Venture Capitalist Screening Criteria and Its Associated Tools: Progressive Screening Matrix and Mean-IRR Index*** by *Lai, M
</div>
</details>
>This course covers the application of financial tools and techniques to the funding and valuation of an entrepreneurial venture. The course seeks to provide students with a background on the venture capital industry, the economic intuition underlying its features, and the basic tools required to work in the industry.

### ESG Investing

>This course focuses on the relevance of sustainability factors on financial performance of firms and securities. Topics in this course include the market terminology, practices, usages and impact of environmental, social and governance (ESG) factors and climate risk. Students will learn to analyze complex financial problems, adapt investment strategies to meet business needs, propose solutions that maximize stakeholder value, and apply ESG related concepts to the process of investment management and valuation.

### Quantitative Trading

>Working in groups, the students will bring together all the knowledge learned in the program to develop and execute a quantitative trading strategy through a simulated platform. The instructor will guide the students through the following stages: (1) idea generation, (2) strategy backtesting, (3) risk management planning, (4) system development, (5) trade execution, and (6) performance evaluation. Students will also have the opportunity to develop their leadership and presentation skills.

### Introduction to Artificial Intelligence and Big Data in Finance
<details>
<summary>Study material</summary>
<div markdown="1">
- ***Fixed Income Analysis*** by CFA Institute
- ***Fixed Income Securities: Valuation. Risk and Risk Management*** by Veronesi
</div>
</details>
>This provides an overview of the main branches of AI and Big Data, and exposes students to real-world industry use cases to help them understand the impact that AI will have on the finance industry. Upon completion of this course, students will be able to identify and leverage AI and Big Data to enhance and/or disrupt business models, while keeping in mind social and ethical considerations.

## Undergraduate Accounting
### Principles of Accounting I
<details>
<summary>Study material</summary>
<div markdown="1">
- ***Financial Accounting*** by Libby, Libby, and Hodge
</div>
</details>
>This is the first course of the principles of accounting sequence. Introduction to the concepts and principles of financial accounting, including the analysis, recording, and reporting of business transactions and preparation of financial statements.

### Principles of Accounting II
<details>
<summary>Study material</summary>
<div markdown="1">
- ***Managerial Accounting*** by Whitecotton, Libby, and Phillips
</div>
</details>
>This is the second course of the principles of accounting sequence. It introduces concepts, accounting methods, and analytical tools related to managerial and cost accounting. Topics include fundamental cost concepts, job-order and process costing systems, CVP analysis, budgets and standards, segment reporting, and decision-making using cost information.

### Financial Accounting I
<details>
<summary>Study material</summary>
<div markdown="1">
- ***Intermediate Accounting*** Kieso, Donald E., Weygandt, Jerry J. AND Warfield, Terry D
</div>
</details>
>Study of the application of generally accepted accounting principles to accounting for business organizations; evaluation of balance sheet accounts and the related effects on income determination.

### Financial Accounting II
<details>
<summary>Study material</summary>
<div markdown="1">
- ***Intermediate Accounting*** Kieso, Donald E., Weygandt, Jerry J. AND Warfield, Terry D
</div>
</details>
>Special problems in accounting for owner's equity and long-term liabilities including corporate bonds, leases, deferred taxation and pensions.

## Undergraduate Economics
### Microeconomics
<details>
<summary>Study material</summary>
<div markdown="1">
- ***Microeconomics*** by M. Parkin
</div>
</details>
>Theory of the firm in a free enterprise system; theory of consumer demand; market structures and resource allocation; selected topics on government regulation.

### Macroeconomics
<details>
<summary>Study material</summary>
<div markdown="1">
- ***Macroeconomics*** by Blanchard, Olivier
</div>
</details>
>Theory of national income determination and business fluctuation; monetary and fiscal policies; selected topics in macroeconomic policies and open economy macroeconomics.

### Introduction to Econometrics
<details>
<summary>Study material</summary>
<div markdown="1">
- ***Introduction to Econometrics*** by Stock, James and Mark Watson
</div>
</details>
>Topics on the use of statistical regression techniques in modeling and estimating economic and business relationships. Both theoretical and applied aspects are addressed.

## Undergraduate Information System
### Introduction to Information Systems
<details>
<summary>Study material</summary>
<div markdown="1">
- ***Information Systems: A Manager’s Guide to Harnessing Technology*** by John Gallaugher
</div>
</details>
>Information systems (IS) is about managing the applications of IT to create business values. Topics include fundamental concepts of IS, e-commerce, digital and internet economy, web 2.0 and social networks, online advertising, personalization and privacy, digital rights management and piracy, business intelligence and decision-making, how organizations harness IS for innovative business strategies, and the socio-economic impact of IS on organizations and societies.

### Business Statistics
<details>
<summary>Study material</summary>
<div markdown="1">
- ***Statistics for Business Decision Making and Analysis*** by Robert Stine and Dean Foster
</div>
</details>
>Collection, tabulation and presentation of numerical data; concepts of probability and probability distributions; sampling; statistical estimation and hypothesis testing; correlation and regression analysis.

### Introduction to Business Analytics
<details>
<summary>Study material</summary>
<div markdown="1">
- ***Python Data Science Handbook*** by Jake Vanderplas
</div>
</details>
>This introduces students with the foundation needed to apply data analytics to real-world challenges they will confront in their future career. It covers statistical tools in descriptive analytics and predictive analytics, including multiple linear regression, logistic regression and clustering. Emphasis is placed on applications, concepts and interpretation of results, rather than theory and calculations. Students use a computer software for data analysis.

### Operations Management
<details>
<summary>Study material</summary>
<div markdown="1">
- ***Matching Supply with Demand*** by Cachon and Terwiesch
- ***Operations and Supply Chain Management*** by Jacobs and Chase
</div>
</details>
>Production and service operations viewed from the strategic, tactical and operational levels; capacity planning, process selection, impact of technology location and layout, material and resource requirements, scheduling and quality control.

### Data Mining for Business Analytics
<details>
<summary>Study material</summary>
<div markdown="1">
- ***Data Mining for Business Analytics: Concepts, Techniques, and Applications in R*** by Galit Shmueli, Peter C. Bruce, Inbal Yahav, Nitin R. Patel, Kenneth C. Lichtendahl
- ***Data Science for Business: What you need to know about data mining and dataanalytic thinking*** by Foster Provost, Tom Fawcett
- ***Learning Data Mining with Python*** by Robert Layton
</div>
</details>
>This covers the fundamental concepts, technologies, and applications of business analytics to help firms gain a competitive advantage in the era of Big Data. Topics include text mining, predictive analytics, search engine strategy, social network analysis, cloud computing, etc. Students will gain hands-on experience with popular data analytical tools.

### Big Data Technologies
<details>
<summary>Study material</summary>
<div markdown="1">
- ***Hadoop: The Definitive Guide*** by Tom White
- ***Learning Spark: Lightning-Fast Big Data Analysis*** by Holden Karau, Andy Konwinski, Patrick Wendell, and Matei Zaharia
</div>
</details>
>In the era of "Big Data", organizations need a new infrastructure/platform to manage the storage and processing of large volume of data. This course introduces the emerging technological paradigm of big data management, as well as some common approaches that are used to gain insights from big data for business decision-making. In particular, it covers a range of big data technologies, including HDFS, MapReduce, Spark, Hive, Pig, etc., that allow for performing data-intensive analysis.

### Introduction to Probability Models
<details>
<summary>Study material</summary>
<div markdown="1">
- ***A First Course in Probability*** by Sheldon Ross
</div>
</details>
>Probabilities, random variables, distribution functions, densities, expected values, conditional distributions and densities, conditional expectations, moment generating functions, Chebyshev's inequality, central limit theorem, and Poisson processes.

### Business Modeling and Optimization
<details>
<summary>Study material</summary>
<div markdown="1">
- ***Practical Management Science*** by Albright and Winston
</div>
</details>
>The science and technology of informed decision making with focus on optimizing business processes. Spreadsheet decision modeling in Excel will be used throughout. Emphasis on problem formulation, spreadsheet-based solution methods, and managerial insights. Applications to managerial decision problems in diverse industries and functional areas including finance and accounting, human resource, marketing, and operations.

### Statistics for Financial Risk Management
<details>
<summary>Study material</summary>
<div markdown="1">
- ***Elements of Financial Risk Management*** by Peter F. Christoffersen
</div>
</details>
>This provides an introduction to financial risk management. Topics include how to measure market risks, statistical properties of returns and volatility, volatility modeling, Value at Risk (VaR), Risk Metrics, historical simulation, assessing VaR methods and stress testing. Theories will be illustrated by practical examples in financial markets.

### Time Series Analysis and Forecasting
<details>
<summary>Study material</summary>
<div markdown="1">
- ***Elements of Financial Risk Management*** by Peter F. Christoffersen
</div>
</details>
>Review of regression and its application to forecasting problems; moving averages, exponential smoothing, Box-Jenkins, ARIMA models and transfer function models; forecasts of economic, financial and business time series.

### Financial Service Operations Management
<details>
<summary>Study material</summary>
<div markdown="1">
- ***Options, Futures, and Other Derivatives*** by J. C. Hull
- ***Investment Science*** by David G. Luenberger
- ***The Elements of Statistical Learning*** by Trevor Hastie, Jerome Friedman, and Robert Tibshirani
</div>
</details>
>This course focuses on the products, processes and delivery channels in the financial industries. It analyzes and evaluates the designs and performances of the internal operations and the different distribution channels of the financial institutions, and identifies opportunities for continuous improvement in productivity, efficiency and service quality. Issues like operational risk management, application of IT, automation, outsourcing and new trends in the financial service operations for both financial institutions and non-financial institutions will be explored.

## Undergraduate Management
### Business Ethics and the Individual
<details>
<summary>Study material</summary>
<div markdown="1">
- ***Blind Spots: Why We Fail to Do What’s Right and What to Do About It*** by Max Bazerman and Ann Tenbrunsel
</div>
</details>
>This presents and exemplifies three major traditions of ethical thought in East and West moral philosophy - namely utilitarianism, principle-based ethics and virtue-based ethics. Employing guest speakers, lectures, cases, contemporary readings, role-plays, fieldwork, reflective student writing, and discussion groups, the course engages students in a serious consideration of their own ethical standards as applied to their present academic environment and their future careers. Students come to understand through this course that while an ethical dilemma may be viewed in various ways depending on one's guiding assumptions, a decision and course of action nevertheless must be chosen in harmony with one's own moral convictions.

### Business Ethics and Social Responsibility
<details>
<summary>Study material</summary>
<div markdown="1">
- ***Business and Society: Stakeholders, Ethics, Public Policy*** by Lawrence, Anne T. and James Weber
</div>
</details>
>This intermediate business ethics addresses issues of responsible decision-making at the business  level from a stakeholder management perspective.The key purpose of this is to raise awareness and understanding of a select set of complex and challenging ethical and social issues confronting the business leaders of today and tomorrow.Ultimately, this will encourage you to become positive influences in your personal and professional lives.

## Undergraduate Risk Management and Business Intelligence
### Data Analytics with R
<details>
<summary>Study material</summary>
<div markdown="1">
- ***R and Data Mining: Examples and Case Studies*** by Yanchang Zhao
</div>
</details>
>This provides a hands-on introduction to R as a programming language and environment for data analytics and visualization. It will cover the basic syntax including functions and flow control, some commonly used data structures such as vectors, lists, matrices and data frames, as well as data importing and visualization in R. The course will also introduce a few primary data cleaning techniques in dealing with missing values, duplicates and inconsistency, and means to implement simple data transformation and normalization with R. Classic data mining models and the corresponding packages in R will also be presented, with the focus on model fine tuning and parameter calibration for practical applications.

### Practicing Risk Management using Case Studies
<details>
<summary>Study material</summary>
<div markdown="1">
- ***Risk Management and Financial Institutions*** by John C, Hull
</div>
</details>
>This will examine various types of risks that many business enterprises face nowadays; for example, financial markets risks can be further divided into equity risk, foreign exchange risk, credit risk, interest rate risk and commodity risk. In addition, other non-financial risk factors such as operational risk, reputational risk, catastrophe risk (earthquake/typhoon), geopolitical risk, cybersecurity risk, counterparty risk and liquidity risk will also be discussed.

### Introduction to Risk Management and Business Intelligence
<details>
<summary>Study material</summary>
<div markdown="1">
- ***Risk Management and Financial Institutions*** by John C, Hull
</div>
</details>
>This presents basic concepts and techniques for risk management and business intelligence. Various types of risk such as market risk, credit risk and operational risk are discussed with business applications and regulatory issues. Modern development of business intelligence, data management techniques and related applications like financial analysis, risk assessment, customer relationship management and human capital productivity analysis are also presented.

### Life Contingencies Models and Insurance Risk
<details>
<summary>Study material</summary>
<div markdown="1">
- ***Study Guide for the Society of Actuaries Exam LTAM*** by S. Broverman
</div>
</details>
>The topics discussed in this course include survival models, life tables and selection, insurance benefits, annuities, premium calculation, and insurance policy values.

### Advanced Data Mining for Risk Management and Business Intelligence
<details>
<summary>Study material</summary>
<div markdown="1">
- ***Introduction to Data Mining*** by Pang-Ning Tan, Michael Steinbach and Vipin Kumar
</div>
</details>
>Data mining is a process of extracting implicit, previously unknown, and potentially useful knowledge from data, and it is a critical task in many applications. This course will place emphasis on applications of data mining on areas such as business intelligence, which aims to uncover facts and patterns in large volumes of data for decision support. Application areas also include many other areas in science and engineering applications. This course builds on basic knowledge gained in the introductory data-mining, and explores how to more effectively mine large volumes of realworld data and to tap into large quantities of data. It will introduce new algorithms that can more effectively find hidden and profitable data patterns and knowledge. Working on real world data sets, students will experience all steps of a data-mining project. 

## Undergraduate Mathematics
### Applied Statistics
<details>
<summary>Study material</summary>
<div markdown="1">
- ***Probability and Statistics for Engineers and Scientists*** by Ronald E. Walpole, Raymond H. Myers, Sharon L. Myers and Keying Ye. 
</div>
</details>
>A systematic introduction to statistical inference, including the necessary probabilistic background, point and interval estimation, hypothesis testing.

#### Reference

- https://prog-crs.hkust.edu.hk/ugcourse
- https://prog-crs.hkust.edu.hk/pgcourse
- http://stellar.mit.edu/index.html