# ❤️ Heart Stroke Prediction

A Machine Learning web app that predicts the risk of heart disease based on clinical parameters, built with **KNN (K-Nearest Neighbors)** and deployed using **Streamlit**.

---

## 🚀 Demo

Run the app locally:
```bash
streamlit run app.py
```

---

## 📁 Project Structure

```
heart_stroke_prediction/
│
├── app.py                        # Streamlit web application
├── heart_stroke_prediction.ipynb # ML model training notebook
├── KNN_heart.pkl                 # Trained KNN model
├── scaler.pkl                    # StandardScaler for input features
├── columns.pkl                   # Expected input columns
├── requirements.txt              # Python dependencies
└── .gitignore                    # Files to ignore in Git
```

---

## 🧠 Model Details

- **Algorithm:** K-Nearest Neighbors (KNN)
- **Dataset:** Heart Failure Prediction Dataset (UCI / Kaggle)
- **Preprocessing:** Standard Scaling, One-Hot Encoding
- **Target:** Heart Disease (1 = High Risk, 0 = Low Risk)

---

## 📊 Input Features

| Feature | Description |
|---|---|
| Age | Age of the patient |
| Sex | Male / Female |
| ChestPainType | ATA / NAP / ASY / TA |
| RestingBP | Resting Blood Pressure (mm Hg) |
| Cholesterol | Serum Cholesterol (mg/dl) |
| FastingBS | Fasting Blood Sugar > 120 mg/dl |
| RestingECG | Normal / ST / LVH |
| MaxHR | Maximum Heart Rate |
| ExerciseAngina | Exercise Induced Angina (Y/N) |
| Oldpeak | ST Depression |
| ST_Slope | Up / Flat / Down |

---

## ⚙️ Installation

```bash
# Clone the repo
git clone https://github.com/your-username/heart-stroke-prediction.git
cd heart-stroke-prediction

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run app.py
```

---

## 🛠️ Tech Stack

- Python
- Scikit-learn
- Pandas
- Streamlit
- Joblib

---

## 👨‍💻 Author

**Ansh Sharma**  
B.Tech CSE — Sardar Beant Singh State University, Gurdaspur  
Intern @ Solitaire Infosystem, Mohali
