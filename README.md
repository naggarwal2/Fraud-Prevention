# 💳 Fraud Detection Using Machine Learning

## Overview

This project uses machine learning to detect fraudulent financial transactions. We clean the data, engineer meaningful features, train multiple models, and identify the best one for real-time deployment.

## Problem

Fraud is rare (~1%) but costly. Manual detection is slow and outdated. Can we automatically flag fraud before money is lost?

## Tools & Techniques

- **Python**: pandas, scikit-learn, matplotlib  
- **Models**: KNN, Decision Trees, Random Forest, Gradient Boosting, Logistic Regression  
- **Extras**: Isolation Forest (outliers), ANOVA F-test (feature selection)

## Results

- **Best Model**: Random Forest / Gradient Boosting  
- **F1 Score**: ~0.85  
- KNN underperformed on recall

## Lessons

- Data cleaning is critical  
- Imbalanced data skews metrics—use F1, precision, recall  
- Ensemble methods outperform simpler models

## Next Steps

- Deploy best model in real-time  
- Add deep learning for complex fraud  
- Enable continuous retraining




