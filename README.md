# Internship-Tasks
#  Machine Learning  (Tasks 1–5)

This repository contains five machine learning tasks covering data exploration, visualization, classification, and regression using real-world datasets.

---

#  Task 1: Iris Dataset Exploration

##  Objective

To understand and visualize the Iris dataset and analyze relationships between variables.

##  Approach

* Loaded dataset using seaborn
* Explored structure using `.shape`, `.columns`, `.head()`
* Created:

  * Scatter plot (petal length vs width)
  * Histogram (sepal length distribution)
  * Box plot (outlier detection)
* Applied Logistic Regression for classification

##  Results & Insights

* Clear separation between species based on petal features
* Setosa is easily distinguishable
* Model achieved high accuracy in classification

---

#  Task 2: Credit Risk Prediction

## Objective

To predict whether a loan applicant will default on a loan.

##  Approach

* Loaded loan dataset (`loan_dataset_20000.csv`)
* Encoded categorical variables
* Visualized:

  * Loan amount distribution
  * Education level
  * Income vs loan relationship
* Applied Logistic Regression with feature scaling

##  Results & Insights

* Income and credit score strongly influence loan repayment
* Model achieved good accuracy
* Data visualization revealed important financial patterns

---

# Task 3: Customer Churn Prediction

##  Objective

To identify customers likely to leave the bank.

## Approach

* Cleaned dataset and removed unnecessary columns
* Encoded categorical variables (Geography, Gender)
* Visualized:

  * Age distribution
  * Geography distribution
  * Churn comparison by gender
* Used Random Forest classifier
* Analyzed feature importance

## Results & Insights

* Balance, Age, and Geography are key factors
* Random Forest performed well in predicting churn
* Feature importance helped identify major influences

---

#  Task 4: Insurance Claim Prediction

##  Objective

To estimate medical insurance charges based on personal data.

## Approach

* Loaded insurance dataset (`insurance.csv`)
* Encoded categorical variables
* Visualized:

  * Charges distribution
  * BMI vs charges
  * Smoking effect on charges
* Applied Linear Regression
* Evaluated using MAE and RMSE

##  Results & Insights

* Smoking significantly increases insurance charges
* BMI also affects cost
* Model predictions were reasonably accurate

---

#  Task 5: Personal Loan Acceptance Prediction

##  Objective

To predict which customers are likely to accept a personal loan offer.

##  Approach

* Loaded bank dataset (`bank.csv`)
* Encoded categorical features
* Visualized:

  * Age distribution
  * Job categories
  * Marital status vs loan acceptance
* Applied Logistic Regression

##  Results & Insights

* Job type and marital status influence decisions
* Certain customer groups are more likely to accept offers
* Model achieved good classification accuracy

---

#  Overall Conclusion

These tasks demonstrate the complete workflow of machine learning:

* Data preprocessing and cleaning
* Data visualization and analysis
* Model building and evaluation

The results show that machine learning models can effectively predict outcomes and provide valuable insights from real-world datasets.

---
