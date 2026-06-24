# 🚗 Ford Car Price Prediction (Machine Learning Project)

An end-to-end Machine Learning project that predicts the selling price of Ford cars based on features like mileage, engine size, fuel type, transmission, and car model. The project includes data preprocessing, feature engineering, model training, evaluation, and deployment using Streamlit.

---

## 📌 Project Overview

This project demonstrates a complete ML workflow:

- Data Cleaning & Preprocessing  
- Exploratory Data Analysis (EDA)  
- Feature Engineering  
- Encoding & Scaling  
- Model Training & Evaluation  
- Hyperparameter Tuning  
- Model Saving  
- Streamlit Web App Deployment  

---

## 📊 Dataset Features

- model  
- year  
- price (target)  
- mileage  
- fuelType  
- transmission  
- tax  
- mpg  
- engineSize  

---

## 🧠 Feature Engineering

New features created:

- **car_age** = Current Year - year  
- **mileage_per_year** = mileage / car_age  

---

## 🤖 Machine Learning Models Used

- Linear Regression  
- Random Forest Regressor  
- Gradient Boosting Regressor  

### 🏆 Best Model:
Random Forest Regressor (after tuning)

---

## 📈 Model Evaluation

The models were evaluated using:

- Mean Absolute Error (MAE)  
- Root Mean Squared Error (RMSE)  
- R² Score  
- Cross Validation  

---

## 🔧 Tech Stack

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  
- Streamlit  
- Joblib  

---

## 🚀 Web App (Streamlit)

A user-friendly web application was built where users can:

- Select car model  
- Enter mileage, engine size, fuel type, etc.  
- Get instant price prediction  

---

## 📷 Project Workflow
Data Collection → Data Cleaning → EDA → Feature Engineering → Model Training → Evaluation → Deployment


---

## 💡 Key Insights

- Newer cars have higher prices  
- Mileage negatively impacts price  
- Engine size positively affects price  
- Model type strongly influences price  

---

Install Dependencies
pip install -r requirements.txt

Run Streamlit App
streamlit run app.py

📌 Files in This Repository
app.py                  → Streamlit web app  
ford_price_model.pkl    → Trained ML model  
model_features.pkl            → Feature columns  
ford.csv                → Dataset  
requirements.txt        → Dependencies  

🎯 Future Improvements
Try XGBoost / LightGBM
Improve feature engineering
Deploy on cloud (AWS / Render / HuggingFace)
Add API using Flask/FastAPI

👨‍💻 Author

Samia Akram
Aspiring Data Scientist & Machine Learning Engineer
