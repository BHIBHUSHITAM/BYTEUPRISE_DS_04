# TASK-4-BANK_TERM_DEPOSIT_PREDICTION
# Bank Term Deposit Subscription Prediction

## Overview

The "Bank Term Deposit Subscription Prediction" project focuses on predicting whether a client will subscribe to a term deposit. The dataset used is the Bank Marketing Data Set, obtained from the UCI Machine Learning Repository. This classification problem involves addressing class imbalance by using class reweighing and undersampling techniques.

## Project Details

1. **Dataset Description**:
   - The Bank Marketing Dataset contains data related to telemarketing campaigns for a Portuguese banking institution.
   - Features include customer demographics, previous contact history, economic indicators, and campaign outcomes (whether the customer subscribed to a term deposit or not).

2. **EDA Insights**:
   - Some interesting observations from exploratory data analysis (EDA):
     - Students have a higher subscription rate (31%) compared to other groups.
     - Single clients show the highest proportion of subscribers.
     - Illiterate clients subscribed more frequently.
     - Clients with basic education have the lowest subscription rate.
     - Months of March, December, September, and October had higher subscription rates.
     - Thursdays had the highest subscription day of the week.
     - Clients who subscribed had longer median contact durations.
     - Clients with no previous campaign history had higher subscription rates.

3. **Modelling Approach**:
   - The duration variable was dropped due to its impact on the output target (e.g., if duration=0, then y="no").
   - Logistic Regression, RandomForestClassifier, and LGBMClassifier models were used for prediction.

4. **Source**:
   - [Moro et al., 2014](http://dx.doi.org/10.1016/j.dss.2014.03.001)
   - S. Moro, P. Cortez, and P. Rita. A Data-Driven Approach to Predict the Success of Bank Telemarketing. Decision Support Systems.

## License

This project is released under the MIT License, allowing others to use, modify, and distribute the code freely.

Feel free to contribute, share, and collaborate! 📊📈

---
