# Machine-learning-

# 🏥 Insurance Claim Prediction Dataset

This project uses demographic and health-related data to predict whether a customer is likely to make an **insurance claim**. The dataset contains information such as age, sex, BMI, number of children, smoking status, region, and medical charges.

## 📁 Dataset Overview

The dataset consists of **1,338 records** with the following 8 input features and 1 target variable:

| Column Name      | Description                                                                            |
| ---------------- | -------------------------------------------------------------------------------------- |
| `age`            | Age of the insured individual (in years)                                               |
| `sex`            | Gender (`0` = Female, `1` = Male)                                                      |
| `bmi`            | Body Mass Index, a measure of body fat based on height and weight                      |
| `children`       | Number of children covered by health insurance                                         |
| `smoker`         | Smoking status (`0` = Non-smoker, `1` = Smoker)                                        |
| `region`         | Geographic region (`0` = northeast, `1` = northwest, `2` = southeast, `3` = southwest) |
| `charges`        | Annual medical expenses billed to the insurance provider (in USD)                      |
| `insuranceclaim` | Target variable (`1` = Filed insurance claim, `0` = Did not file a claim)              |

## 🔍 Sample Data

```
| age | sex | bmi   | children | smoker | region | charges     | insuranceclaim |
|-----|-----|-------|----------|--------|--------|-------------|----------------|
| 19  | 0   | 27.90 | 0        | 1      | 3      | 16884.92    | 1              |
| 18  | 1   | 33.77 | 1        | 0      | 2      | 1725.55     | 1              |
| 28  | 1   | 33.00 | 3        | 0      | 2      | 4449.46     | 0              |
| 33  | 1   | 22.70 | 0        | 0      | 1      | 21984.47    | 0              |
| 32  | 1   | 28.88 | 0        | 0      | 1      | 3866.86     | 1              |
```

## 🎯 Objective

Build a predictive model that accurately determines whether an individual is likely to **file an insurance claim** based on their personal and health-related data.

## 📊 Potential Applications

* Health insurance risk scoring
* Premium pricing models
* Fraud detection
* Customer segmentation for wellness programs

## 🧠 Suggested ML Models

* Logistic Regression
* Decision Trees / Random Forest
* Gradient Boosting (e.g., XGBoost, LightGBM)
* Neural Networks
* Support Vector Machines (SVM)

## 🧪 Preprocessing Recommendations

* Encode categorical variables (`sex`, `smoker`, `region`)
* Normalize or scale continuous variables like `bmi` and `charges` if needed
* Consider feature interactions (e.g., smoker × bmi)

## 🔧 Files

* `insurance.csv` – The dataset file
* `README.md` – This project description
* *(Optional)* `insurance_claim_prediction.ipynb` – A sample notebook for data exploration and modeling

## ✅ License

This dataset is for educational and research purposes. No real personal or medical data is included.

---
