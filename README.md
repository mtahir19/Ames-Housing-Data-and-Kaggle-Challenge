# Project 2 - Ames Housing Data and Kaggle Challenge

### Problem Statement

While being a Data Scientist, I predicted home sales prices. This may give potential customers a reliable estimate of the value of their property. After gathering required data, I plan to do understanding of data, some Exploratory Data Analysis (EDA), possible cleaning of the data and to deal with missing/null values. I will run different regression models to build a model that predicts the home sale price of home listings in Ames. I believe a better predictive model for home sale prices is crucial; the more business customers it can attract for sure. Therefore, more users means more revenue, a win for my company in such a technological environment.

---

## Executive Summary
I conducted the analysis on the test and training datasets. Each dataset contains 81 columns or features and 2051 rows. I analyzed the test and training scores of online available data.

I tried to include different regression models e.g., 1. Linear Regression; 2. Lasso Regression; 3. Ridge Regression; and 4. Elastic Net Regression.  Lasso, Ridge, and Elastic Net Regression are better performing in feature selection.  I had fun while regularizing, or scaling, and finding the best score in my models. Indeed, tuning coefficients helped me to achieve the increasing the model's predictive accuracy.

When analyzing the datasets, few findings about scores and sales prices were gathered. Here are the most significant findings, focusing primarily on the data:
Significant Correlation of House Prices
Histograms show interesting distribution
Tuning of Hyperparameters and models are exciting
Excellent Score and Root-mean-square error
More time and resources can lead to better result


### Contents:

- [Data Cleaning & Exploratory Data Analysis (EDA)](#EDA)
- [Data Dictionary](#Data-Dictionary)
- [Model Evaluation](#Model-Evaluation)
- [Recommendations](#Business-Recommendations)
- [Sources](#Sources)

---

### Data Cleaning & EDA

1) Read the data, droped Columns deemed useless and remove null values.

2) plot histograms and boxplots and scatter to see relation for better understanding of the given data.

3) I also tried to see distributions using seaborn.

4) I picked numeric columns and changed some colums to get_dummies.

---

### Data Dictionary:

No new features were added, as such, the original data dictionary may be used. It is found here: http://jse.amstat.org/v19n3/decock/DataDocumentation.txt

---


### Evaluation:

According to the expectations, Ames housing price model made the most impact; major due to overall quality, area, basement, second floor, lot and  wood deck. In general, the factors that the models say have an impact on its sales price are within expectations of observable reality. Therefore, my model does give us a better sense of how important each factor is with respect to another.

### Recommendations:

Though experienced real estate agents have an idea what may impact a house's sale price, the model is more reliable in a sense to help them with a better estimate to their clients. I recommend it be used in making housing price estimates to clients. The real estate agent may be able to claim that the estimate is based on past data and not just the agent's individual intuition of home sales prices in the market.
