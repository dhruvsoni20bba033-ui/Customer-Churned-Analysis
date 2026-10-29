# Telco Customer Churn Analysis

Exploratory data analysis of customer churn at a telecommunications company, aimed at finding which customer segments are most likely to leave and what the business can do to retain them.

## Overview

The analysis uses Python to clean the data and explore how customer demographics, tenure, contract type, internet services, supplementary services and payment methods relate to churn. The results are shown through charts and summarized in an executive summary.

## Dataset

- **7,043** customer records and **21** columns
- Covers demographics, account details, subscribed services, billing information and churn status
- Source: *(add the link or name of the dataset here)*

## Key Findings

- **Overall churn:** 1,869 of 7,043 customers (**26.54%**) have churned, about one in four.
- **Contract type:** Month-to-month customers churn at **42.71%**, against 11.27% for one-year and 2.83% for two-year contracts.
- **Internet service:** Fiber optic customers churn at **41.89%**, more than twice the DSL rate (18.96%).
- **Online security and tech support:** Customers without these services churn at about **42%**, against about 15% for customers who have them.
- **Payment method:** Electronic check users churn at **45.31%**, against 15–19% for the other payment methods.
- **Senior citizens:** They churn at **41.68%**, against 23.61% for non-seniors.
- **Gender:** There is almost no difference (26.92% female vs 26.16% male).
- **Tenure:** Churn is concentrated among customers in their first few months of service.

## Recommendations

1. Improve onboarding and early support for new customers.
2. Test incentives to move month-to-month customers to longer contracts.
3. Investigate the reasons behind fiber optic churn.
4. Look into billing issues among electronic check users.
5. Offer relevant security and support bundles.
6. Provide targeted support for senior customers.

## Limitations

The analysis is exploratory and shows associations, not causes. Next steps would be statistical testing, multivariable analysis, predictive modeling and a financial impact estimate.

## Repository Contents

| File | Description |
|---|---|
| `Customer Churn.csv` | Raw dataset |
| `Telco_Customer_Churned_Analysis.ipynb` | Python code for data cleaning, analysis and visualizations |
| `Telco_Churn_Executive_Summary.pdf` | Full executive summary with detailed tables and analysis |

## Tools Used

Python, Pandas, NumPy, Matplotlib, Seaborn
