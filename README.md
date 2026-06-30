# Cardiovascular-Disease-AI-Model
This is the AI-Model to Detect the Cardiovascular Disease 
❤️ Cardiovascular Disease Prediction using Machine Learning
📌 Overview

This project predicts the likelihood of cardiovascular disease using machine learning techniques. It uses patient health records to build and compare multiple classification models, helping identify individuals at higher risk of heart disease. The project includes data preprocessing, exploratory data analysis (EDA), visualization, model training, evaluation, and prediction.

📂 Dataset

The project uses the Cardiovascular Disease Dataset (cardio_train.csv), which contains patient information such as:

Age
Gender
Height
Weight
Blood Pressure
Cholesterol Level
Glucose Level
Smoking Status
Alcohol Consumption
Physical Activity
Cardiovascular Disease (Target)
🛠 Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Joblib
Google Colab / Jupyter Notebook
🤖 Machine Learning Models

The following algorithms are implemented and compared:

Logistic Regression
K-Nearest Neighbors (KNN)
Decision Tree
Random Forest
Support Vector Machine (SVM)

Each model is evaluated using Accuracy, Precision, Recall, F1-Score, and Confusion Matrix. The best-performing model is saved for future predictions.

🚀 Features
Data Cleaning and Preprocessing
Exploratory Data Analysis (EDA)
Correlation Heatmap
Data Visualization
Feature Scaling
Model Training and Comparison
Model Saving using Joblib
Prediction on New Patient Data
📁 Project Structure
Cardiovascular-Disease-Prediction/
│── cardio_train.csv
│── Cardiovascular_Disease_Prediction.ipynb
│── heart_disease_model.pkl
│── scaler.pkl
│── README.md
│── requirements.txt
▶️ How to Run
Clone the repository.

Install the required libraries:

pip install -r requirements.txt
Open the notebook in Google Colab or Jupyter Notebook.
Run all cells to train the models and make predictions.
