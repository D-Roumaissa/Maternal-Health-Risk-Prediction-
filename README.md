# Maternal-Health-Risk-Prediction-
```markdown
# Maternal Health Risk Prediction 🩺

This repository contains a Machine Learning project focused on predicting health risk levels for pregnant patients. By analyzing physiological data, the model classifies risks into **High**, **Mid**, or **Low**, enabling early intervention and better maternal care.

---

## 📌 Project Overview
Maternal mortality and complications remain a significant global health challenge. This project leverages data science to identify patterns in vital signs that correlate with pregnancy risks.

### Key Objectives:
*   Perform Exploratory Data Analysis (EDA) on maternal health data.
*   Train multiple classification models to find the most accurate predictor.
*   Evaluate model performance using Confusion Matrices and Classification Reports.

---

## 📊 Dataset Features
The model is trained on the following medical parameters:
*   **Age:** Age of the patient.
*   **SystolicBP:** Upper value of Blood Pressure (mmHg).
*   **DiastolicBP:** Lower value of Blood Pressure (mmHg).
*   **BS:** Blood Sugar levels (mmol/L).
*   **BodyTemp:** Body temperature (°F).
*   **HeartRate:** Resting heart rate (bpm).
*   **RiskLevel:** Target variable (High Risk, Mid Risk, Low Risk).

---

## 🛠️ Installation & Usage

1. **Clone the repo:**
   ```bash
   git clone [https://github.com/D-Roumaissa/Maternal-Health-Risk-Prediction-.git](https://github.com/D-Roumaissa/Maternal-Health-Risk-Prediction-.git)

```

2. **Install requirements:**
```bash
pip install pandas numpy scikit-learn matplotlib seaborn

```


3. **Run the Analysis:**
Open the Jupyter Notebook or run the main script:
```bash
jupyter notebook Maternal_Health_Risk.ipynb

```



---

## 🧪 Model Performance

The project compares several algorithms:

| Model | Accuracy |
| --- | --- |
| Random Forest | ~80-85% |
| Decision Tree | ~78% |
| Support Vector Machine | ~70% |
