---
title:  "Study Roadmap for Finance"
excerpt: "Banking, Securities markets, Venture capital and private equity, Fintech and financial innovation, Green finance and others.."

categories:
  - fina-general
tags:
  - [Finance]

toc: false
toc_sticky: false
 
date: 2022-09-25
last_modified_at: 2022-09-26
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


        subgraph Economics and Finance
        ECON2174[Mathematics for Economists]
        ECON3113[Microeconomic Theory I]
        ECON3133[Microeconomic Theory II]
        ECON3143[Macroeconomic Theory II]
        ECON3334[Introduction to Econometrics]
        end

        ECON2113 --> ECON3113
        ECON3113 --> ECON3133
        ECON3113 & ECON3123 --> ECON3143
        ISOM2500 --> ECON3334


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
        FINA5120 & FINA5210 --> FINA5670
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
- Microeconomic Theory I
- Macroeconomic Theory I
- Microeconomic Theory II
- Macroeconomic Theory II
- Introduction to Econometrics
- Time Series Econometrics and Business Forecasting

# Undergraduate Information Systems
- Introduction to Information Systems
- Coding for Business
- Business Statistics
- Introduction to Business Analytics
- Operations Management
- Business Applications Programming
- Data Mining for Business Analytics
- Big Data Technologies
- Introduction to Probability Models
- Statistics for Financial Risk Management
- Statistical Analysis of Financial Data in R/S-plus
- Time Series Analysis and Forecasting

# Undergraduate Management
- Business Ethics and the Individual
- Oprganizational Behavior
- Business Ethics and Social Responsiblity

# Undergraduate Marketing
- Marketing Management

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