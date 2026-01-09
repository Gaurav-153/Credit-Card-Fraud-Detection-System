💳 Credit Card Fraud Detection using Machine Learning
📌 Project Overview

This project focuses on detecting fraudulent credit card transactions using machine learning techniques.
The dataset is highly imbalanced, making fraud detection a challenging task. The goal of this project is to accurately identify fraudulent transactions while minimizing missed fraud cases.
.

📂 Dataset :

Source: Kaggle – Credit Card Fraud Detection Dataset

Link: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

Description:
1.Contains credit card transactions made by European cardholders
2.Includes numerical features transformed using PCA
3.Target column Class:
  0 → Non-fraud
  1 → Fraud

⚙️ Technologies Used:
Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn
XGBoost
SHAP

🚀 How to Run the Project:
Download the dataset from Kaggle
Place creditcard.csv in the same directory as the notebook
Open Test.ipynb using Jupyter Notebook or Google Colab
Run all cells sequentially


🧪 Project Workflow :
1️⃣ Data Preprocessing & EDA
Loaded and inspected the dataset
Checked for missing values and duplicate records
Analyzed class imbalance
Visualized data distributions and correlations
Scaled Amount and Time features using StandardScaler

2️⃣ Model Training & Evaluation :
The following machine learning models were trained and evaluated:
Logistic Regression
Random Forest
XGBoost
Evaluation Metrics Used:
Accuracy
Precision
Recall
F1-score
ROC-AUC
Due to class imbalance, Recall and ROC-AUC were prioritized over Accuracy.

3️⃣ Model Optimization & Explainability :
Performed hyperparameter tuning using GridSearchCV
Selected XGBoost as the final model based on performance
Analyzed feature importance
Used SHAP to explain model predictions
Conducted a basic fairness check based on transaction amount groups

📊 Key Results :
XGBoost performed best in identifying fraudulent transactions
Hyperparameter tuning improved recall and overall model reliability
SHAP provided clear insights into feature contributions
The model showed consistent behavior across different transaction amounts

✅ Conclusion :
This project demonstrates an end-to-end machine learning pipeline for fraud detection, covering data preprocessing, model training, optimization, and explainability. The final model is suitable for real-world fraud detection scenarios where identifying fraudulent transactions is critical.
