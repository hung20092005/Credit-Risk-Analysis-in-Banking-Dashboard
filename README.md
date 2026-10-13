# 📊 Credit Risk Analysis Dashboard
Interactive Dashboard Link: https://app.powerbi.com/view?r=eyJrIjoiZDMwOTA0MWQtMGUxNS00ZGJkLTg1MTUtYzRmMjE0YjI3MDE3IiwidCI6IjQ2NTRiNmYxLTBlNDctNDU3OS1hOGExLTAyZmU5ZDk0M2M3YiIsImMiOjl9

## 👤 Author
* Hiep Dylan
* LinkedIn: https://www.linkedin.com/in/hiepledai-dylan/

Example: Individuals with less than one year of work experience have the highest default rate (27.94%). When clicking on the “<1 year” column in the chart, we can further drill down into the data as follows. Within this group (<1 YOE), at the time of the loan, unemployed individuals have the highest default rate (27.94%). They typically borrow for medical expenses or debt consolidation. If we only analyze Job Type in isolation, we would not uncover this insight! (Dashboard page 1)

## 📌 Overview

This project focuses on analyzing credit risk in a banking dataset to understand borrower behavior, loan distribution, and key factors driving loan default.

The objective is to uncover insights that support better credit risk assessment and portfolio management using data-driven approaches.

---

## 🎯 Objectives

* Analyze loan portfolio distribution across different customer segments
* Identify key drivers of default risk
* Develop a risk segmentation framework (Low, Medium, High)
* Build an interactive dashboard for exploratory analysis

---

## 📂 Dataset

The dataset includes borrower demographics, financial indicators, and loan-related attributes, such as:

* Income, employment type, and home ownership
* Loan amount, interest rate, and loan term
* Debt-to-income ratio and credit utilization
* Past delinquencies and default history

---

## 📊 Key Metrics

* Total Loan Amount
* Default Rate
* Average Loan Amount
* Debt-to-Income Ratio (DTI)
* Loan-to-Income Ratio (LTI)

---

## 📈 Dashboard Features

* Interactive Power BI dashboard with slicers and drill-down functionality
* Risk segmentation based on financial and behavioral indicators
* Multi-level analysis across employment type, loan purpose, and borrower profile
* Dynamic comparison of default patterns across segments

---

## 🔍 Key Insights

* Higher debt-to-income and credit utilization ratios are strongly associated with increased default risk
* Borrowers with past delinquencies or prior defaults show significantly higher risk
* Employment stability and loan purpose further influence default patterns
* Certain segments combine high risk with high loan exposure, indicating potential portfolio vulnerabilities

---
# 📊 Dashboard Pages
## 🎯 1. Credit Risk Overview
### Overall Risk
![image_alt](https://github.com/ledaihiepdylan/Credit-Risk---Banking-Analysis-Hiep-Dylan/blob/68843a9d8952c4cf1a058bbe176ced7f7855d822/Source/Overview.jpg)

The dataset includes 32,581 borrowers, with a total loan exposure of approximately $312M. Among them, 7,108 borrowers (21.82%) have defaulted, indicating a relatively high overall default rate.

### Gender Distribution
* Male: ~50.25%
* Female: ~49.75%

Demographic factors such as gender, employment type are relatively evenly distributed across the dataset. Additionally, there are no significant differences in default rates among these groups.

### Loan Grade

*Lower grades (D–G) represent extreme default risk
*However, Grades A–C still account for a large portion of total loan volume

### Age Agroup
* Highest default rate: 60+ group
* Lower but still notable: younger groups

---
## Risk Exposure 
![image_alt](https://github.com/ledaihiepdylan/Credit-Risk---Banking-Analysis-Hiep-Dylan/blob/92437698013357af74b348d9462700f35e503d0e/Source/Risk%20Analysis%201.jpg)

### Loan Intent
Loan purposes such as Debt Consolidation, Medical, and Home-related loans account for the highest proportions, while categories like Education and Venture are lower.

Different loan purposes reflect different financial pressures. High-frequency categories may indicate structural demand, but also potential concentration of risk.

### Employment Stability (Years of Exerience)

Default rate is highest for: 
* Unknown
* < 1 year experience

And decreases as experience increases. Employment stability is a clear driver of risk, less experience -> unstable income -> higher default probability

### Loan Term
There is no correlation between the loan term and the default rate.

### Default History
Past default behavior is a strong predictor of future default, confirming that credit history is one of the most important risk indicators.

* 67.27% of borrowers have defaulted before
* Only 32.73% have clean history

### DTI (Debt-to-Income)
* Low (<20%) → lowest risk
* Medium (20–40%) → moderate
* High (41–60%) → high
* Very High (>60%) → highest

There is a strong positive relationship between debt burden and default risk. The higher the proportion of income allocated to total debt obligations, the greater the likelihood of default

![image_alt](https://github.com/ledaihiepdylan/Credit-Risk---Banking-Analysis-Hiep-Dylan/blob/92437698013357af74b348d9462700f35e503d0e/Source/Risk%20Analysis%202.jpg)

### Loan Grade

Default rate increases sharply from Grade A to G. A–C are relatively low default rates. But G: nearly 100% default rate

### Interest Rate

Very High (>16%) interest group shows significantly higher default rate. There is a clear relationship between interest rate and default risk, higher-risk borrowers are charged higher interest rates

### Past Delinquencies

Borrowers with major past delinquencies show higher default rates than “clean” profiles. Even before default happens, repayment issues are already visible


### Loan-to-Income Ratio (LTI)
* Low (<20%) → lowest risk
* Medium (20–40%) → moderate
* High (41–60%) → high
* Very High (>60%) → highest

This confirms a strong positive correlation between financial burden and default risk. The more income is allocated to loan repayment, the higher the likelihood of default

## Geographic Risk Distribution
![image_alt](https://github.com/ledaihiepdylan/Credit-Risk---Banking-Analysis-Hiep-Dylan/blob/92437698013357af74b348d9462700f35e503d0e/Source/Location.jpg)

Default rates do not significantly so much across regions. However, Canada ranks highest, followed by the USA and the UK.  

At the city level, Vancouver (Canada) has the highest default rate among all locations.


## 🛠 Tools & Technologies

* Power BI
* DAX (Data Analysis Expressions)
* Data Modeling & Visualization

---


