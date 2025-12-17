# Bank_Marketing_Campaign_Deposit_Prediction

## Overview
The types of financial products used by the public are more varied. One financial product that is well-known to the public is term deposits. The term deposit mechanism is that a customer deposits a sum of money at a bank or a financial institution, and the money can only be withdrawn after a certain period of time. As compensation, customers will be given a fixed interest according to the nominal amount of money deposited. Nevertheless, as business entities with financial products and respective customers, banks still have to compete to not lose customers. One of the ways to acquire new customers is by conducting a marketing campaign.

To achieve that, machine learning is used to predict the prospective customers that are likely to make deposits.

## Stakeholder

**Investor**

The Bank Investors: benefit from improved campaign efficiency, higher conversion rates, and increased profitability

**User**

Business Development Team: prioritizes high-potential customers based on model predictions

## Goals

- To develop a machine learning classification model that can accurately predict customers with a high likelihood of subscribing to a term deposit.

- To identify the most influential features that affect a customer’s decision to make a term deposit.

- To support the design of more effective and targeted marketing strategies for customer acquisition.

## Project Output

- Best model: LightGBM classification

- Result: Accuracy (0.827), F1-score (0.818), Precision (0.82), Recall (0.81)

- Cost Benefit Analysis: LightGBM model can increase the deposit by **19.03%**, minimize the opportunity cost by **40.62%**, and reduce the wasted cost by **49.48%**

## Recommedation

1. Data Recommendations

    - More comprehensive demographic attributes, such as education level, detailed employment categories, or income segments.

    - More detailed customer interaction history, such as response time to previous calls or messages, call duration, and communication channels used (phone, email, SMS).

2. Model Recommendations

    - Explore advanced ensemble techniques, including stacking or blending multiple high-performing models (Random Forest, LightGBM, CatBoost).

3. Business Recommendations

    - The model should primarily be used by **Marketing and Business Development teams** as a decision-support tool, and **Customer Relationship Management (CRM) teams** to prioritize prospective customers.

    - The model is recommended to be retrained every **3–6 months**, depending on the changes in customer behavior, new marketing strategies, and economic conditions or regulatory updates.

    - The model is most effectively used:
     
        - Before marketing campaigns begin, to create a prioritized list of potential customers.

        - During campaigns, to evaluate performance and adjust outreach strategies.

        - After campaigns, to analyze results and extract insights for future initiatives.
