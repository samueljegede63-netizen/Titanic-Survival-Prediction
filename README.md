# Titanic Survival Prediction 🚢

## Project Overview

I analyzed passenger data from the Titanic disaster to understand the key factors that influenced survival and to build machine learning models that predict survival outcomes.

This project demonstrates a full data science workflow including data cleaning, exploratory data analysis, feature engineering, model building, and model evaluation.

---

## Problem Statement

Given passenger information such as age, gender, ticket class, and fare, the goal is to predict whether a passenger survived the Titanic disaster.

This is a binary classification problem:
- 0 → Did not survive
- 1 → Survived

---

## Dataset

The dataset is the classic Titanic dataset commonly used for beginner machine learning projects. It contains information such as:

- Passenger class (Pclass)
- Sex
- Age
- Number of siblings/spouses aboard (SibSp)
- Number of parents/children aboard (Parch)
- Fare
- Embarked location

---

## Workflow

1. Business Problem
2. Data Loading
3. Initial Exploration
4. Data Cleaning
5. Exploratory Data Analysis
6. Feature Engineering
7. Model Development
   - Logistic Regression
   - Decision Tree
   - Naive Bayes
8. Model Evaluation & Comparison
9. Conclusions

---

## Key Insights

- Gender was the strongest predictor of survival.
- First-class passengers had significantly higher survival rates.
- Third-class passengers had the lowest survival rates.
- Younger passengers had slightly higher survival probability.
- Socioeconomic status played a major role in survival outcomes.

---

## Business Insight

This project demonstrates how historical passenger data can be used to identify survival patterns and build predictive models.

From a business/analytical perspective, the findings show that demographic and socioeconomic factors such as gender and passenger class had the strongest influence on survival outcomes.

This type of analysis can be applied in real-world scenarios such as risk modeling, customer segmentation, and decision support systems.

---

## Model Performance

| Model | Accuracy |
|------|---------|
| Decision Tree | 82.12% |
| Logistic Regression | 80.45% |
| Naive Bayes | 78.21% |

Decision Tree performed best overall, but Logistic Regression provided better interpretability.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Project Structure
