Markdown
# Titanic Survival Prediction
 
## Project Overview
 
This project predicts passenger survival on the Titanic using machine learning techniques.
 
The project includes:
 
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Decision Tree Modeling
- Pre-Pruning
- Hyperparameter Tuning with GridSearchCV
- Post-Pruning using Cost Complexity Pruning
- Feature Importance Analysis
- Kaggle Submission
 
---
 
## Business Problem
 
The objective is to identify which passenger characteristics are associated with survival and build a classification model capable of predicting survival outcomes.
 
---
 
## Dataset
 
Source:
Kaggle Titanic Competition
 
Training Dataset:
891 passengers
 
Target Variable:
Survived
 
---
 
## Feature Engineering
 
Created additional variables:
 
- FamilySize
- IsAlone
- FarePerPerson
 
---
 
## Machine Learning Models
 
### Base Decision Tree
 
Accuracy: 0.748
 
Precision: 0.692
 
Recall: 0.703
 
F1 Score: 0.698
 
### GridSearchCV Optimized Tree
 
Accuracy: 0.800
 
Precision: 0.811
 
Recall: 0.672
 
F1 Score: 0.735
 
### Post-Pruned Decision Tree
 
Accuracy: 0.813
 
Precision: 0.787
 
Recall: 0.750
 
F1 Score: 0.768
 
---
 
## Key Findings
 
Most important predictors:
 
1. Sex
2. Passenger Class
3. Fare Per Person
4. Age
5. Family Size
 
---
 
## Technologies
 
Python
 
Pandas
 
NumPy
 
Matplotlib
 
Seaborn
 
Scikit-Learn
 
---

 Titanic Survival Prediction
Project Overview
This project predicts passenger survival on the Titanic using machine learning techniques.

The project includes:

Data Cleaning
Exploratory Data Analysis (EDA)
Feature Engineering
Decision Tree Modeling
Pre-Pruning
Hyperparameter Tuning with GridSearchCV
Post-Pruning using Cost Complexity Pruning
Feature Importance Analysis
Kaggle Submission
Business Problem
The objective is to identify which passenger characteristics are associated with survival and build a classification model capable of predicting survival outcomes.

Dataset
Source: Kaggle Titanic Competition
## Author
 
Liana Graham
