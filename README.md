# Churn Prediction
---

## Executive summary
The churn dataset is highly imbalanced: with 20.37% of staff churn vs 79.63% No churn, giving an imbalance ratio ≈ 3.9:1. Gradient Boosting (GB) model achieved the best precision (0.73) and accuracy (0.86), but low recall (0.50). Conversely, Decision tree (DT) achieved high recall (0.80) and accuracy (0.75), but poor precision (0.45), indicating a trade-off between avoiding false positives (GB) and capturing staff with the most likelihood to churn (DT). Features with the strongest linear correlation with churn were:  
* Age
* Geography_Germany
* Balance  

---

## Table of contents  
[Problem statement](#problem-statement)  
[Aim and Objectives](#aim-and-objectives)  
[Data and preprocessing](#data-and-preprocessing)  
[Highlighted results from EDA](#highlighted-results-from-eda)    
[Modeling and evaluation](#modeling-and-evaluation)  
[Recommendations](#recommendations)  
[Conclusion](#conclusion) 

---

## Aim

---

## Data and preprocessing
* Dataset shape (10000, 14)
* Target: 'Churn'
* No null or Duplicate values found
* Outliers handled using the IQR method

---

## Highlighted results from EDA

### 1. Distribution of Promotions
* No Churn (0): 7,963 (79.63%)
* Churn (1):    2,037 (20.37%)
> [!NOTE]
> **Imbalance ratio: ~ 3.9 : 1**

![target distribution](target_distr.png)

### 2. 

## Modeling and evaluation

---

## Recommendations

---

## Conclusion 
