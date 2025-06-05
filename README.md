 Mobile Payment Fraud Detection
🔍 Overview
This project focuses on detecting fraudulent mobile payment transactions using machine learning. Leveraging a publicly available dataset, the goal is to identify suspicious activities that deviate from typical user behavior and reduce financial risks in digital payment ecosystems.

🧾 Dataset
Source: Mobile Payment Fraud Dataset on Kaggle

Description: The dataset contains various transaction details such as amount, transaction type, origin and destination, and a binary target column indicating fraud.

🚀 Key Highlights
Conducted detailed Exploratory Data Analysis (EDA) to understand transaction types and fraud distribution.
Data preprocessing included handling class imbalance, feature scaling, and encoding categorical variables.

Implemented multiple ML models for fraud detection:
TensorFlow

Evaluated models using metrics like:

Precision
Recall
F1-score

🛠️ Tech Stack
Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn
Jupyter Notebook

📈 Results
Addressed severe class imbalance using techniques like class_weight='balanced' and SMOTE.
Visualized important features influencing model predictions using feature importance plots.

🧠 Learnings
Gained deeper insight into handling imbalanced datasets in fraud detection scenarios.
Understood the significance of using recall-focused evaluation in high-risk domains like payments.
Strengthened skills in EDA, preprocessing pipelines, and ensemble ML models.
