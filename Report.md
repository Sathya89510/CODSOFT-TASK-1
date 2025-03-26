# Titanic Survival Prediction Report

## 1. Introduction
This report documents the development of a machine learning model to predict survival on the Titanic.

## 2. Data Exploration
- Dataset contains 891 entries with 12 features
- Key features: Pclass, Sex, Age, Fare, Embarked
- Target variable: Survived (0 = No, 1 = Yes)

## 3. Methodology
- Data preprocessing: Handling missing values, feature engineering
- Models tested: Logistic Regression, Random Forest, Gradient Boosting
- Evaluation metric: Accuracy

## 4. Results
| Model               | Accuracy | Precision | Recall |
|---------------------|----------|-----------|--------|
| Logistic Regression | 0.78     | 0.75      | 0.69   |
| Random Forest       | 0.82     | 0.81      | 0.72   |
| Gradient Boosting   | 0.83     | 0.82      | 0.74   |

## 5. Conclusion
The Gradient Boosting model performed best with 83% accuracy...
