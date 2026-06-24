🩺 Diabetes Health Prediction using Machine Learning
📌 Overview

This project aims to predict the likelihood of diabetes using machine learning models based on health indicators from CDC BRFSS 2021 datasets.

Early detection of diabetes can significantly improve prevention and treatment outcomes.

🎯 Objective

To build a machine learning model that classifies individuals into:

0 → No Diabetes
1 → Prediabetes or Diabetes

(or multi-class depending on dataset)

📊 Dataset Description

The project uses CDC Behavioral Risk Factor Surveillance System (BRFSS 2021) datasets:

1️⃣ Imbalanced Dataset
236,378 records
21 features
Target: Diabetes_binary
Classes: 0 (No Diabetes), 1 (Diabetes)
2️⃣ Balanced Dataset (50/50 Split)
67,136 records
21 features
Balanced target distribution
3️⃣ Multi-class Dataset
236,378 records
3 classes:
0 → No Diabetes
1 → Prediabetes
2 → Diabetes
⚙️ Workflow
Data Cleaning
Exploratory Data Analysis (EDA)
Handling Imbalanced Data (if needed)
Feature Selection
Model Training
Model Evaluation
🤖 Machine Learning Models Used
Logistic Regression
Random Forest
XGBoost (optional)
Decision Tree
📈 Evaluation Metrics
Accuracy
Precision
Recall
F1-score
ROC-AUC Curve
🖼️ Results

Example confusion matrix:

(add your image here in images/ folder)

![Confusion Matrix](images/confusion_matrix.png)
🚀 Key Insights
Balanced datasets improve model performance
Feature selection improves accuracy
Random Forest performed best (example)
🛠️ Technologies Used
Python
Pandas
NumPy
Scikit-learn
Matplotlib / Seaborn
📦 Installation
git clone https://github.com/your-username/Diabetes-Health-Prediction.git
cd Diabetes-Health-Prediction
pip install -r requirements.txt
▶️ How to Run
jupyter notebook notebooks/diabetes_model.ipynb
👩‍💻 Author

Meriam Aziz

⭐ Future Improvements
Deploy model using Streamlit or Flask
Add real-time prediction app
Improve feature engineering
Hyperparameter tuning
