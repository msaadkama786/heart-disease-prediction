# Heart Disease Prediction Project
## <a href="http://localhost:8501/">Project Description<</a>


Developed a machine learning model to predict the likelihood of heart disease based on patient medical data. The project involved data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and deployment using Python and Streamlit.

## Technologies Used
Python
Pandas
NumPy
Matplotlib
Scikit-learn
Streamlit
Joblib

## Dataset Features

Common features include:

Age
Sex
Chest Pain Type (cp)
Resting Blood Pressure (trestbps)
Cholesterol (chol)
Fasting Blood Sugar (fbs)
Resting ECG (restecg)
Maximum Heart Rate (thalach)
Exercise-Induced Angina (exang)
ST Depression (oldpeak)
Slope
Number of Major Vessels (ca)
Thalassemia (thal)
Target (Heart Disease: Yes/No)

## Project Workflow
Load the dataset.
Clean and preprocess the data.
Perform Exploratory Data Analysis (EDA).
Split data into training and testing sets.
## Train multiple machine learning models:
1.Logistic Regression
2.Decision Tree
3.Random Forest
4.Support Vector Machine (SVM)
5.K-Nearest Neighbors (KNN)
## Evaluate models using:
1.Accuracy
2.Precision
3.Recall
4.F1 Score
5.Confusion Matrix
Save the best model using Joblib.
Build a Streamlit web application for predictions.
Machine Learning Algorithms
Algorithm	Purpose
Logistic Regression	Binary classification
Decision Tree	Rule-based prediction
Random Forest	Ensemble learning
SVM	Classification with hyperplanes
KNN	Distance-based classification
Evaluation Metrics
Accuracy
Precision
Recall
F1 Score
ROC-AUC Score
Confusion Matrix
Resume Project Description

# Heart Disease Prediction using Machine Learning

Built a predictive machine learning model using Python and Scikit-learn to classify heart disease risk.
Performed data cleaning, feature engineering, and exploratory data analysis (EDA).
Compared Logistic Regression, Random Forest, Decision Tree, SVM, and KNN models to identify the best-performing algorithm.
Developed an interactive Streamlit web application for real-time heart disease prediction.
GitHub README Description

Heart Disease Prediction is a machine learning project that predicts the likelihood of heart disease using patient clinical data. The project includes data preprocessing, visualization, model training, performance evaluation, and deployment with Streamlit for an interactive user experience.

# Folder Structure
# Heart-Disease-Prediction/
│
├── app.py
├── heart.csv
├── model.pkl
├── train_model.py
├── requirements.txt
├── README.md
├── notebooks/
│   └── Heart_Disease_EDA.ipynb
├── static/
└── images/
Sample requirements.txt
streamlit
pandas
numpy
scikit-learn
matplotlib
joblib
Deployment

# You can deploy the project for free using:

Streamlit Community Cloud
GitHub
Render
Hugging Face Spaces

Since you recently asked about deploying Streamlit apps, this project is well suited for deployment on Streamlit Community Cloud by pushing the code to GitHub and connecting the repository to your Streamlit account.
