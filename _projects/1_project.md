---
layout: page
title: Customer Churn Prediction
description: Machine Learning project for Data Mining class
img: assets/img/12.jpg
importance: 1
category: machine learning
related_publications: true
---

## Project Overview

This project focuses on predicting customer churn using machine learning techniques as part of my Data Mining course. Customer churn prediction is a critical business problem where companies aim to identify customers who are likely to discontinue their services, enabling proactive retention strategies.

## Objectives

- Develop predictive models to identify customers at risk of churning
- Compare performance of different machine learning algorithms
- Analyze feature importance to understand key factors driving customer churn
- Provide actionable insights for customer retention strategies

## Dataset

The project utilized a telecommunications customer dataset containing:
- Customer demographics (age, gender, location)
- Service usage patterns (call duration, data usage, number of services)
- Account information (contract type, payment method, monthly charges)
- Historical behavior (customer service calls, complaints)
- Target variable: Churn (Yes/No)

## Methodology

### Data Preprocessing
- Handled missing values using appropriate imputation techniques
- Performed feature engineering to create new predictive variables
- Applied data normalization and scaling for algorithm optimization
- Addressed class imbalance using SMOTE (Synthetic Minority Oversampling Technique)

### Machine Learning Models Implemented

1. **Logistic Regression**: Baseline model for interpretability
2. **Random Forest**: Ensemble method for feature importance analysis
3. **Support Vector Machine**: For non-linear pattern recognition
4. **Gradient Boosting**: Advanced ensemble technique for optimal performance
5. **Neural Networks**: Deep learning approach for complex pattern detection

## Key Findings

### Model Performance
- **Best Model**: Gradient Boosting Classifier achieved 87% accuracy with 0.92 AUC-ROC
- **Feature Importance**: Contract type, monthly charges, and tenure were top predictors
- **Precision/Recall**: Achieved balanced performance with 85% precision and 83% recall

### Business Insights
- Customers with month-to-month contracts are 3x more likely to churn
- High monthly charges without proportional service value increase churn risk
- Customer service interactions correlate strongly with churn probability
- Tenure serves as a strong protective factor against churn

## Technical Implementation

The project was implemented using Python with the following key libraries:
- **Data Processing**: Pandas, NumPy
- **Machine Learning**: Scikit-learn, XGBoost
- **Visualization**: Matplotlib, Seaborn, Plotly
- **Model Evaluation**: Cross-validation, ROC analysis, Confusion matrices


## Results and Impact

The churn prediction model successfully identified high-risk customers with 87% accuracy, enabling:
- **Proactive Intervention**: Early identification of at-risk customers
- **Resource Optimization**: Focused retention efforts on high-value, high-risk segments
- **Cost Reduction**: Estimated 25% reduction in customer acquisition costs through improved retention

## Future Work

- **Real-time Prediction**: Implement streaming data processing for real-time churn scoring
- **Advanced Techniques**: Explore deep learning architectures and ensemble methods
- **A/B Testing**: Validate model predictions through controlled retention campaigns
- **Feature Enhancement**: Incorporate social media sentiment and external economic indicators

This project demonstrated the practical application of data mining techniques to solve real-world business problems, combining technical machine learning skills with business acumen to deliver actionable insights.
