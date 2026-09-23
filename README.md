# Health Insurance Cross-Sell Analysis

## Project Overview
Exploratory analysis of 381,109 customer records from a vehicle insurance cross-sell campaign, identifying which customer characteristics and combinations of characteristics are most associated with a positive response to the offer.

## Key Insight
Two features dominate the response signal: whether a customer already has insurance, and whether their vehicle has prior damage. These compound rather than substitute for each other, isolating a clear high-value segment for targeted outreach.

## Key Findings
| Segment | Response Rate |
|---|---|
| Overall | 12.26% |
| Not previously insured | 22.55% |
| Previously insured | 0.09% |
| Vehicle damage = Yes | 23.77% |
| Vehicle damage = No | 0.52% |
| **Best segment** (not insured + damaged + age 30-39 + vehicle 1-2yrs, n=23,693) | **35.36%** |

## Notebook
[Full analysis notebook](https://github.com/LouisOlaoluwa/Health-Insurance-Cross-Sell-Analysis/blob/main/Health_Insurance_Cross_Sell_Prediction%20Analysis.ipynb)

**Response rate heatmap**
<img width="1608" height="690" alt="Previous Insurance and age group by response" src="https://github.com/user-attachments/assets/cfbcb35a-2fa0-41c7-9d86-db435adf0afd" />

[**other charts**](https://github.com/LouisOlaoluwa/Health-Insurance-Cross-Sell-Analysis/tree/main/Charts)

## Skills Demonstrated
Exploratory data analysis · multivariate segmentation · sample-size and statistical caution · business interpretation

## Tools
Python · Pandas · NumPy · Matplotlib · Seaborn · Jupyter Notebook

## Analysis Structure
1. Data cleaning and validation
2. Univariate and bivariate analysis
3. Multivariate segmentation
4. Policy sales channel analysis
5. Business interpretation

## Limitations
Findings represent associations within this dataset, not causal relationships. Response-rate differences were explored descriptively and not formally tested for statistical significance.

## Dataset
Kaggle: [Health Insurance Cross Sell Prediction](https://www.kaggle.com/datasets/anmolkumar/health-insurance-cross-sell-prediction)
