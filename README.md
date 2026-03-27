# Credit Card Fraud Detection using Machine Learning
## Overview
This project focuses on detecting fraudulent credit card transactions using machine learning techniques. The dataset is highly imbalanced, where fraudulent transactions represent a very small percentage of total data.
## Problem Statement
Credit card fraud is a major issue in financial systems. Due to the rarity of fraud cases, it is challenging to build models that accurately identify them without increasing false alarms.
## Objectives
- Detect fraudulent transactions from a large dataset  
- Handle highly imbalanced data effectively  
- Evaluate model performance using appropriate metrics  
## Methodology
- Data preprocessing and feature selection  
- Handling class imbalance using stratified train-test split  
- Model training using Random Forest Classifier  
- Model evaluation using confusion matrix, ROC curve, and classification report  
## Results
- Achieved ROC-AUC score of approximately 0.93–0.98  
- Very low false positives and strong fraud detection capability  
- Effective performance on highly imbalanced data  
## Visualizations
- Class distribution plot (shows imbalance in dataset)  
- Confusion matrix heatmap (model performance summary)  
- ROC curve (model evaluation)  
## Tech Stack
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  
## How to Run
1. Clone the repository  
2. Install dependencies  
   pip install -r requirements.txt  
3. Open and run the notebook  
## Dataset
The dataset used is a publicly available credit card transaction dataset.
(Dataset not included due to size/privacy. Can be downloaded from public sources.) 
## Outputs
### Class Distribution
![Class Distribution](outputs/class_distribution.png)
### Confusion Matrix
![Confusion Matrix](outputs/confusion_matrix.png)
### ROC Curve
![ROC Curve](outputs/roc_curve.png)
## Future Improvements
- Apply advanced techniques like SMOTE for better imbalance handling  
- Try other models like XGBoost or Neural Networks  
- Deploy as a real-time fraud detection system  
