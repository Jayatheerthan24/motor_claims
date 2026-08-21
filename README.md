#  Insurance Claims – Exploratory Data Analysis

##  Project Overview

This project performs Exploratory Data Analysis (EDA) and Data Visualization on a motor insurance claims dataset.

The main goal is to identify unusually high claims and find patterns that may indicate cases requiring fraud investigation.

---
##  Objectives
- Load the insurance claims dataset using Pandas.
- Clean and standardize the dataset.
- Handle missing and duplicate values.
- Analyze claim amounts and previous claim counts.
- Calculate the claim-to-policy-value ratio.
- Group customers based on previous claim count.
- Identify unusual claim amounts using statistical analysis.
- Visualize claim patterns using Matplotlib and Seaborn.
- Prepare a fraud-review priority report.

---
## Technologies Used

- Python
- Pandas
- Matplotlib
- Google Colab

---

##  Dataset
The dataset contains motor insurance claim information, including:

| Feature | Description |
|---|---|
| Claim Amount | Amount claimed by the customer |
| Policy Value | Value covered by the insurance policy |
| Incident Description Length | Length of the incident description |
| Previous Claim Count | Number of previous claims made by the customer |
| Claim Outcome | Result/status of the claim |

##  Round II – Exploratory Data Analysis

The following steps are performed:

1. Import the claims dataset into Pandas.
2. Inspect the dataset structure and data types.
3. Check for missing values.
4. Remove duplicate records.
5. Standardize claim and policy currency values.
6. Calculate descriptive statistics for claim amounts.
7. Analyze previous claim counts for each claim outcome.
8. Calculate the claim-to-policy-value ratio.
9. Group customers based on their previous claim count.
10. Detect unusually high claim amounts using the IQR method.

### Round III – Data Visualization
## Box Plot
Understand the distribution of claim amounts.
Detect extreme values.
Identify unusually high claims.

## Scatter Plot
A Scatter Plot is used to analyze the relationship between:
Previous Claim Count → Claim Amount
This helps identify customers with repeated claims and unusually high claim values.

Additional Visualizations -- 
Claim Amount Distribution
Claim Ratio Distribution
Outlier Analysis
## Fraud Review

Claims are given higher priority for review when they show one or more of the following characteristics:

Very high claim amount.
High claim-to-policy-value ratio.
Multiple previous claims.
Claim amount identified as an outlier.
Combination of multiple suspicious characteristics.

These cases can be forwarded to the fraud-review team for detailed investigation.

## Results

Unusually high insurance claims.
Customers with frequent previous claims.
High claim-to-policy-value ratios.
Potential outliers requiring further investigation.
Patterns associated with potentially suspicious claims.

The visualizations provide an easy way to understand claim patterns and prioritize cases for fraud review.
