# Heart_Disease_Prediction
❤️ Heart Disease Prediction using Machine Learning

📌 Project Overview

Heart disease is one of the leading causes of death worldwide. Early prediction can help in timely medical intervention and prevention.
In this project, I built a machine learning model to predict the presence of heart disease based on various medical attributes.

The project includes Exploratory Data Analysis (EDA), model training, performance evaluation, and model comparison to select the best-performing model.

🎯 Problem Statement

To develop a machine learning model that can accurately predict whether a person has heart disease based on clinical and demographic features.

📊 Dataset

Dataset contains medical attributes such as:

Age

Sex

Chest pain type

Resting blood pressure

Cholesterol level

Fasting blood sugar

Maximum heart rate

Exercise-induced angina

And other relevant features

Target variable:

1 → Presence of heart disease

0 → Absence of heart disease

🔍 Exploratory Data Analysis (EDA)

Used Seaborn and Matplotlib for data visualization

Analyzed relationships between features and target variable

Identified important trends and patterns affecting heart disease

Visualized distributions and comparisons across different features

🧠 Machine Learning Models Used

The following models were trained and evaluated:

Logistic Regression

Decision Tree Classifier

Random Forest Classifier

📈 Model Evaluation Metrics

To ensure reliable model comparison, the following evaluation techniques were used:

Confusion Matrix

Accuracy Score

ROC Curve

AUC Score

🏆 Results & Conclusion

All three models were evaluated and compared using ROC-AUC scores

Logistic Regression performed the best, providing a strong balance between simplicity and performance

ROC curve analysis confirmed Logistic Regression as the most reliable model for this dataset

Out of the three model Logistic Regression and Random Forest Regressor have an AUC of 0.93 whereas Decision Tree have AUC of 0.88.On comparing accuracy Logistic Regression have outperformed other two model having an accuracy of nearly 85%.Also the AP(Average precision) for logistic regression model is 94% which matches the AP of Random Forest hence by accuracy comparison Logistic Regression model is best but both Logistic regression and Random FOrest Classifier can be used for this data set

🛠️ Technologies & Libraries Used

Python

NumPy

Pandas

Matplotlib

Seaborn

Scikit-learn

Acknowledgement

The dataset used in this project was obtained from Kaggle and is publicly available for educational and research purposes. Proper credit is given to the original data contributors. This project is intended solely for learning and demonstration of machine learning techniques and does not represent a clinical diagnostic tool.
