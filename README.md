# Banking-Marketing-Prediction

Term deposits are a major source of income for a Portuguese banking institution. Client's money is invested for an agreed rate of interest over a fixed amount of time, or term. The bank has various outreach plans to sell term deposits to their customers such as email marketing, advertisements, telephonic marketing, and digital marketing.

Telephonic marketing campaigns still remain one of the most effective way to reach out to people. However, they require huge investment as large call centers are hired to actually execute these campaigns. Hence, it is crucial to identify the customers most likely to convert beforehand so that they can be specifically targeted via call.

The result of this project is that we managed to **increase our conversion rate by 14.73%**. We have also analyzed the most important factors affecting conversion rate with their respective correlations. We also provide rational and achieveable recommendations that can be applied by the relevant team so that the conversion rate of the company can increased.

## Project Background

In the marketing field, conversion rate metric is one of the most important metrics to pay attention to. In this case, bank needs to increase the conversion rate as optimally as possible so that the bank's revenue can also increase. `Current bank's conversion rate only 11%`. From this condition our goal is to `increase conversion rate up to 14%`. Then we need to analyze factors that cause low conversion rate and also
predict customer will convert or not.

## Dataset Overview

Our data consist of 41.188 bank's client. There are 20 independent features and 1 target feature. Our target feature explain whether the client will subscribe term of deposit or not. Data Source: [link](https://www.kaggle.com/datasets/prakharrathi25/banking-dataset-marketing-targets)


## Data Preprocessing :

1. Handling Duplicated Values
2. Feature Engineering
3. Feature Encoding
4. Feature Scaling
5. Feature Selection
6. Handling Imbalanced Target

## Modeling

We use 7 types of algorithm:

1. Logistic Regression
2. KNeighborsClassifier
3. Decission Tree Classifier
4. Random Forest
5. Ada Boosting Classifier
6. Gradient Boosting Classifeir
7. XGB Classifier

**Scoring :**
Recall Score, we want to minimize num of False Negative (Predicted will subscribe term of deposit, actually not subscribe)

**Result**
Random Forest has highest Recall Score
1. Train recall score : 0.85
2. Test recall score: 0.83

**Top 4 Feature Importances:**
1. contact
2. pdays
3. poutcome_succes
4. previous

Recommendation:

For re-marketing purpose, our recommendation is to target only cellular users, who had contacted recently, and they are around 30-50 years old
Implementing this strategy can **increase Conversion Rate up to 14.73%**


