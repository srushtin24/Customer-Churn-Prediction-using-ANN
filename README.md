# Customer Churn Prediction Using ANN (Artificial Neural Network) 
This repository contains two complete models for predicting customer churn using Artificial Neural Networks (ANN) built with TensorFlow/Keras. The objective is to analyze telecom customer behavior and predict whether a customer will churn or stay.
What makes this project strong is that it includes both a baseline ANN model and an enhanced version with imbalanced data handling (SMOTE).<br>

**Dataset :** https://www.kaggle.com/datasets/blastchar/telco-customer-churn<br><br>

📂 ***Files Included in This Repository***<br>

Customer churn prediction using ANN             
- Standard ANN model trained on the original dataset<br>

Customer churn prediction using ANN - 2
- Improved ANN model using SMOTE to handle class imbalance<br><br>

🚀 Model 1 — Baseline ANN (Without Handling Imbalance)<br>

📌 Dataset Nature → Imbalanced<br>
Churn = Yes (minority) < Churn = No (majority)<br>

![report1](report1.png)<br>
![cm1](cm1.png)<br>

📈 Good accuracy, but imbalance affects churn detection performance.<br><br>


🚀 Model 2 — ANN + SMOTE (Imbalanced Data Solved)<br>

📌 Dataset Nature → SMOTE was applied to oversample minority churn class — balancing dataset.<br>

Churn = 0<br>
Before       : 5163<br>
After SMOTE  : 5163<br>

Churn = 1<br>
Before       : 1869<br>
After SMOTE  : 5163 (balanced)<br>

![report2](report2.png)<br>
![cm2](cm2.png)<br>

📈 Balanced recall between churn vs non-churn
📈 Much better customer churn detection
📈 More business actionable model

