# 🫀 Heart Disease Risk Level Predictor

This is a machine learning-based web application that predicts the **risk level of heart disease** based on basic clinical and lifestyle inputs. The model is trained using the **Linear Regression** algorithm and deployed through a simple web interface.

---

## 📷 Screenshots

### 🏠 Home Page

![Home Page](https://github.com/Kaveesha0316/Heart-Disease-Risk-Level-Predictor/blob/main/Images/Screenshot%202025-08-01%20235835.png)

### 📊 Result Page

![Result Page](https://github.com/Kaveesha0316/Heart-Disease-Risk-Level-Predictor/blob/main/Images/Screenshot%202025-08-01%20235816.png)

*(Update image paths as needed based on your GitHub directory structure)*

---

## 🚀 Features

- Collects patient data via a clean and modern form
- Predicts heart disease risk using a trained ML model
- Displays predicted risk level with real-time processing
- Easy-to-use interface for both clinical and educational use

---

## 🧠 Machine Learning Model

- **Algorithm**: Linear Regression
- **Library**: `scikit-learn`
- **Dataset**: Medical dataset with attributes like age, cholesterol, blood pressure, diabetes, smoking status, etc.
- **Model Output**: A numerical value representing the predicted risk level

---

## 🧪 Input Fields

- Name  
- Gender 
- Age  
- TC (Total Cholesterol in mg/dL)  
- HDL (High-Density Lipoprotein in mg/dL)  
- SBP (Systolic Blood Pressure in mm Hg)  
- Smoke   
- Blood Pressure Medication 
- Diabetics

---

## 🛠️ Technologies Used

- **Frontend**: HTML, CSS  
- **Backend**: Python (Flask)  
- **ML Model**: scikit-learn (Linear Regression)  
- **Model Persistence**: joblib  

---

## 🧾 How to Run Locally

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/heart-disease-risk-predictor.git
   cd heart-disease-risk-predictor

2. Install dependencies:
   pip install -r requirements.txt

3. Run the app:
   python app.py

4. Open in your browser:
   http://127.0.0.1:5000
