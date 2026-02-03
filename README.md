# Heart_disease_project

# Heart Disease Prediction App  
Live Demo: https://heartdiseaseproject-mohit.streamlit.app  

This is a Machine Learning–powered **Heart Disease Prediction App** built using  
**Python, Streamlit, and Scikit-learn**.  
Users can enter their medical parameters (age, blood pressure, cholesterol, diabetes status, etc.)  
and the model predicts the **risk of heart disease**.

---

## 🚀 Features

- Simple and intuitive **Streamlit UI**
- Predicts heart disease using a trained **KNN Machine Learning Model**
- Uses `scaler.pkl` for consistent input scaling
- Uses `columns.pkl` for correct feature ordering
- Real-time prediction with clear “High Risk / Low Risk” output
- Fully deployed online using **Streamlit Cloud**

---

## 📁 Project Structure

heart_disease_prediction/
│── app.py
│── KNN_heart.pkl
│── scaler.pkl
│── columns.pkl
│── requirements.txt
│── README.md


---

## 🧠 Machine Learning Model Details

- **Algorithm:** K-Nearest Neighbors (KNN)
- **Problem Type:** Binary Classification (0 = No Risk, 1 = High Risk)
- **Preprocessing:**
  - StandardScaler for numerical features
  - Preprocessed columns saved in `columns.pkl`
- **Model File:** `KNN_heart.pkl`
t
