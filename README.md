SmartPremium: Predicting Insurance Costs with Machine Learning
Welcome to SmartPremium, a machine learning project that predicts insurance premium costs based on customer demographics, financials, and health-related features. This project uses preprocessing pipelines, feature engineering, and regression models to make accurate predictions. The final app is deployed using Streamlit, and model tracking is managed with MLflow.

📌 Project Structure
bash
Copy
Edit
SmartPremium/
│
├── app.py                 # Streamlit web app for prediction

├── best_model.pkl         # Trained ML model (Scikit-learn pipeline)

├── requirements.txt       # Required packages

└── README.md              # Project documentation

📊 Dataset
The dataset contains customer profiles, vehicle info, health scores, feedback, and past claim history.

📁 Download Dataset:
https://drive.google.com/drive/folders/1_8RrBdfx3iitQnX1C9y0RYvocQ1Y16r9?usp=drive_link

Replace the above link with your actual shared Google Drive link.

🚀 Features Used
Demographic: Age, Gender, Marital Status, Number of Dependents

Financial: Annual Income, Credit Score

Health & Lifestyle: Health Score, Smoking Status, Exercise Frequency

Policy: Policy Type, Insurance Duration, Previous Claims, Policy Start Date

Others: Location, Property Type, Vehicle Age, Customer Feedback

🔧 Machine Learning Stack
Preprocessing: ColumnTransformer, Pipeline

Model: XGBoostRegressor, with GridSearchCV for tuning

Logging & Tracking: MLflow

App Deployment: Streamlit

Saving Model: joblib as best_model.pkl

🌐 Web App Preview
Launch the web app using:

bash
Copy
Edit
streamlit run app.py
The app includes:

Project Intro Page – Overview of the problem and solution

Prediction Page – Input form and premium prediction

Creator Info Page – Your details

