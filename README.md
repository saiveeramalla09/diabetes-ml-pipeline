# diabetes-ml-pipeline

# Diabetes Prediction — ML Pipeline

# Author : Sai Veeramalla

## Overview
Binary classification to predict diabetes
using Pima Indians dataset (768 patients)

## Models Compared
| Model | Accuracy | Std Dev |
|-------|----------|---------|
| Logistic Regression | 0.7722 | 0.0224 |
| Random Forest | 0.7748 | 0.0278 |
| Decision Tree | 0.7462 | 0.0367 |
| KNN | 0.7670 | 0.0239 |
| Naive Bayes | 0.7513 | 0.0186 |
| Neural Network | 0.7657 | 0.0211 |

## Best Model
Logistic Regression
- Most consistent (lowest std)
- Explainable to medical professionals
- Similar accuracy to Random Forest

## Key Findings
- Glucose, BMI, Age are strongest predictors
- Dataset is imbalanced (500 vs 268)
- Recall for diabetes class = 0.64

## Tech Stack
Python, Scikit-learn, Pandas, 
Seaborn, Matplotlib
