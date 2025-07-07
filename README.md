❤️ Heart Disease Prediction using XGBoost
About the Project
Hi! This project is about building a machine learning model to predict the chances of heart disease in patients. The goal is to help with early detection using a patient’s health data. Quick and accurate predictions can really make a difference in saving lives.

Problem Statement
Heart disease is one of the biggest health issues worldwide. Many people don’t even know they have it until it's too late. I wanted to build a model that could predict the presence of heart disease based on medical features like age, blood pressure, cholesterol, and more.

Dataset
The dataset I used contains patient health records. Here are some of the features:

Feature	Description
Age	Patient's age
Sex	1 = Male, 0 = Female
ChestPainType	Type of chest pain
RestingBP	Resting blood pressure (mm Hg)
Cholesterol	Cholesterol level (mg/dl)
FastingBS	Fasting blood sugar > 120 mg/dl (1 = Yes)
RestingECG	Resting ECG results
MaxHR	Maximum heart rate achieved
ExerciseAngina	Exercise-induced angina (1 = Yes, 0 = No)
Oldpeak	ST depression induced by exercise
ST_Slope	Slope of peak exercise ST segment
Target	1 = Heart disease, 0 = No heart disease

What I Did
Cleaned the dataset

Scaled the features using MinMaxScaler

Checked class distribution (it was balanced, so no oversampling was needed)

Built an XGBoost Classifier

Tuned hyperparameters using GridSearchCV

Model Performance
The final model performed quite well!

Accuracy: ~83%

Precision for class 0: 82%

Precision for class 1: 83%

Balanced results, no major class bias.

Tools Used
Python

XGBoost

Pandas

Scikit-learn

Matplotlib & Seaborn (for visualization)

How to Run
Clone this repo

Install the required libraries (you can use pip install -r requirements.txt if you want to create the file)

Open the Jupyter Notebook

Run all the cells

What’s Next
I’d like to:

Try other models like Random Forest and Logistic Regression for comparison

Maybe deploy this using Streamlit for real-time prediction

Explore model explainability using SHAP values

Contact
If you have suggestions or want to collaborate, feel free to reach out!

Aniket Susgohar
GitHub Profile
