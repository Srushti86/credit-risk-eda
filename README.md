Credit Risk Analysis — Exploratory Data Analysis
An exploratory data analysis (EDA) project on loan application data to identify patterns and factors associated with credit default risk using Pandas and Seaborn.

📌 Problem Statement
Financial institutions face significant losses due to loan defaults. Understanding the patterns behind credit risk is critical for making informed lending decisions. This project analyses 100,000+ loan application records to uncover key risk indicators and default patterns.

📂 Dataset

Source: Loan application dataset
Size: 100,000+ records
Files Used:

Application data (current loans)
Previous application data (historical loans)


Target: Credit default (0 = No default, 1 = Default)


🛠️ Technologies Used

Python
Pandas, NumPy
Matplotlib, Seaborn


⚙️ Methodology

Data Cleaning — Handling missing values, outlier detection, data type correction
Feature Engineering

Age categories (binned from days of birth)
Credit amount categories


Univariate Analysis — Distribution of individual features
Bivariate Analysis — Relationship between features and default status
Multivariate Analysis — Interaction between multiple variables
Dataset Merging — Application data merged with previous application records
Pivot Tables — Default rate analysis across income groups and gender
Visualizations — Heatmaps, bar charts, box plots, distribution plots


📊 Key Findings

Dataset is heavily imbalanced — only 8.07% of applicants defaulted (TARGET=1), while 91.93% repaid successfully.

Cash loans dominate — 90.5% of all loan applications were cash loans; revolving loans had a smaller share.

Most applicants fall in the 25–45 age group (51.9%), followed by 45–65 (41.2%); applicants below 25 are rare (5.3%).

Low and medium credit amounts are most common — 31.5% fell in the Low Credit category (up to ₹2,00,000).

Income and credit amount show weak correlation (0.157) — higher income does not strongly predict higher loan amounts.

Defaulters (TARGET=1) tend to be younger — correlated with lower years of employment and shorter credit history.

Previous application data merged with current applications to enrich analysis across 1.67 million historical records.
