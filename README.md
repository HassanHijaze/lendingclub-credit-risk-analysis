# LendingClub Credit Risk Analysis

## Project Overview
This project analyzes LendingClub loan data to predict whether a borrower will fully repay a loan or not. The goal is to explore credit risk patterns and build machine learning models that classify loan outcomes based on borrower and loan characteristics.

## Objective
The main objective of this project is to use historical loan data to identify patterns related to repayment behavior and apply classification models to predict default risk.

## Dataset
The dataset used in this project contains LendingClub loan information, including borrower financial details, credit history, and loan-related features.

## Tools and Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Project Steps
1. Data loading and exploration  
2. Data cleaning and preprocessing  
3. Exploratory data analysis (EDA)  
4. Feature preparation  
5. Model training using Decision Tree and Random Forest  
6. Model evaluation using classification metrics  

## Files
- `lendingclub_credit_risk.ipynb` 

## Models Used
- Decision Tree Classifier
- Random Forest Classifier

## Results
The Random Forest model performed better overall than the Decision Tree model. However, the results also showed that the model predicted the majority class more effectively than the minority class. This means the model was better at identifying loans that were fully paid than loans that were not fully paid.

## Key Insight
This project highlights that accuracy alone is not enough when working with imbalanced data. In credit risk prediction, recall for risky loans is especially important because missing high-risk borrowers can be costly.

## Conclusion
This project demonstrates a complete machine learning workflow, from data exploration and visualization to model building and evaluation. It also shows the challenges of predicting minority-class outcomes in credit risk problems.

## Author
Hassan Hijazi
