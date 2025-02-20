# Credit Risk Prediction using Machine Learning

## Overview

This project builds a credit risk prediction model using machine learning techniques to classify customers based on their likelihood of loan default. The model is deployed using Streamlit for an interactive user interface.

## Key Features
* Machine Learning Models Used: Logistic Regression, Decision Tree, Random Forest, and XGBoost.
* Best Model: XGBoost achieved 96% accuracy, outperforming other models.
* Evaluation Metrics: AUC-ROC, precision-recall curves, confusion matrices.
* Deployment: Interactive Streamlit web app for real-time predictions.

## Technologies Used
* Programming Language: Python
* Libraries: NumPy, Pandas, Scikit-Learn, XGBoost, Matplotlib, Seaborn, Streamlit
* Deployment: Streamlit

## Dataset
The model uses customer credit history, loan details, and bureau data to predict credit risk (customers.csv, loans.csv, bureau_data.csv) .

## Model Performance
* XGBoost Accuracy: 96%
* Performance Metrics:
* High precision and recall for risk classification.
* AUC-ROC curve used for evaluation
* Optimized hyperparameters to reduce false positives.

## Future Enhancements
* Automated Feature Engineering: Use AutoML frameworks or feature selection techniques like Recursive Feature Elimination (RFE) to improve model accuracy.
*  Real-Time Data Processing: Implement Kafka or FastAPI to handle real-time loan application data for instant risk assessment.
*  Cloud Deployment: Deploy the model on AWS, Azure, or GCP for scalability, integrating with databases like PostgreSQL or MongoDB.

