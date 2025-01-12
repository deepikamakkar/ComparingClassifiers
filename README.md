# ComparingClassifiers: Bank Marketing Campaigns Dataset Analysis and Modeling

## Problem Statement
Analyze the data of direct marketing campaigns (phone calls) of a Portuguese banking institution using multiple maching learning models and help predict if the client will subscribe a term deposit (variable y).

## Data Overview
This data set is obtained from https://archive.ics.uci.edu/dataset/222/bank+marketing and is related with direct marketing campaigns (phone calls) of a Portuguese banking institution. The classification goal is to predict if the client will subscribe a term deposit (variable y).

##### Dataset Information
The data is related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed.

There are four datasets:

- bank-additional-full.csv with all examples (41188) and 20 inputs, ordered by date (from May 2008 to November 2010), very close to the data analyzed in [Moro et al., 2014]
- bank-additional.csv with 10% of the examples (4119), randomly selected from 1), and 20 inputs.
- bank-full.csv with all examples and 17 inputs, ordered by date (older version of this dataset with less inputs).
- bank.csv with 10% of the examples and 17 inputs, randomly selected from 3 (older version of this dataset with less inputs). The smallest datasets are provided to test more computationally demanding machine learning algorithms (e.g., SVM).
  
The classification goal is to predict if the client will subscribe (yes/no) a term deposit (variable y).

## Data Pre Processing
##### Dataset: 4,119 entries, 21 columns.

##### Feature Set:
Categorical - [job, marital, education, default, housing,loan, contact, month, day_of_week, poutcome]

Numeric- [age, duration, campaign, pdays, previous, emp.var.rate, cons.price.idx, cons.conf.idx, euribor3m, nr.employed]

Target Variable - [ yes, no]

## Data Modelling & Metrics
##### Modelling using four classified Models:
- K-Nearest Neighbors (KNN)
- Decision Trees
- Logistic Regression
- Support Vector Machines (SVM)

##### Metrics for Evaluation used:
- Accuracy
- Precision
- Recall
- F1-Score
- AUC-ROC Curve


## Conclusion
- Logistic regression performs is best and is the right choice for this dataset  
- Decision tree is suitable to recall(yes)

## Next Steps
1. **Deploy Model in Prod**: You can deoloy model in Prod and continue the evaluation of model on varied dataset.
2. **Enhance Model Usage**: You should use other models like Random Forest to derive futher accuracy of model.
3. **Support Campaign using the data:** To make the more people subscribe, use this data to apply to identified age group, martial status, imcome groups.
