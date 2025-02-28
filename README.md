Ensembling Logistic Regression with SMOTE for Credit Card Fraud Detection
Overview
With the increasing reliance on digital transactions, credit card fraud has become a major concern. This project implements a credit card fraud detection system using Ensembling Logistic Regression with SMOTE to handle data imbalance. The system uses machine learning techniques to classify fraudulent transactions with high precision while minimizing false positives.

Features
Machine Learning Models: Logistic Regression, Random Forest, SVM, Neural Networks
Data Preprocessing: Feature scaling, handling missing values
Class Imbalance Handling: Synthetic Minority Over-sampling Technique (SMOTE)
Performance Metrics: Precision, Recall, F1-score, Confusion Matrix, AUPRC
Visualizations: Precision-Recall Curve, Model Comparisons
Methodology
Data Preprocessing:

Standardization of the ‘Amount’ column
Missing values handled using SimpleImputer
Splitting data into features (X) and target variable (y)
Handling Class Imbalance:

SMOTE is applied to balance the dataset
Creates synthetic samples for fraudulent transactions
Model Training:

Trains Logistic Regression as the primary classifier
Compares performance with other models like Random Forest, Gradient Boosting, and SVM
Model Evaluation:

Analyzes accuracy, precision, recall, and F1-score
Uses confusion matrices for fraud detection efficiency
Compares different models for the best fraud detection approach
Results
Models are evaluated based on precision, recall, and AUPRC
False positives and false negatives are minimized
The system identifies fraudulent transactions efficiently
Installation
Clone the repository:
sh
Copy
Edit
git clone https://github.com/yourusername/credit-card-fraud-detection.git
cd credit-card-fraud-detection
Install dependencies:
sh
Copy
Edit
pip install -r requirements.txt
Run the training script:
sh
Copy
Edit
python train.py
Usage
Modify the dataset in the data/ directory
Adjust hyperparameters in config.py
Run the model and check evaluation metrics
Contributors
Kandi Sneha - Email
Khaja Mohammad Fazil Afzal Shareef - Email
Marumanula Bhanu Sri - Email
Kolli Manish Moses - Email
G. Geetha (Assistant Professor) - Email
