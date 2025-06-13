# ✈️ Predicting Air Crash Severity

This project aims to develop a machine learning-based system to predict the severity of air crashes using historical crash data. By leveraging data analysis and predictive modeling techniques, this project attempts to identify the key factors associated with fatal and non-fatal incidents in aviation.

---

## 📌 Objective

- Load and preprocess real-world aviation crash data.
- Perform Exploratory Data Analysis (EDA) to understand underlying trends and features.
- Train classification models to predict whether an air crash is **severe** or **non-severe**.
- Evaluate models using appropriate performance metrics.

---

## 📁 Repository Contents

| File | Description |
|------|-------------|
| `Predicting Air Crash Severity.ipynb` | Main Jupyter notebook with all code: preprocessing, EDA, modeling, and results |
| `README.md` | Project documentation |
| `requirements.txt` | Required Python libraries (optional, add if needed) |
| `data/` (if applicable) | Folder to store dataset files |

---

## 📊 Data Overview

> *(Adjust this section according to your dataset)*

The dataset contains records of air crashes, including features like:
- Date and time of the crash
- Location
- Number of fatalities and survivors
- Aircraft type and operator
- Weather or mechanical conditions (if available)
- Summary and cause (if applicable)

The target variable is typically the **Severity**, labeled as:
- `0`: Non-Severe
- `1`: Severe (e.g., with high fatalities or complete loss)

---

## 🔍 Exploratory Data Analysis

The notebook explores:
- Class distribution (severe vs. non-severe)
- Feature correlations (e.g., number of fatalities vs. severity)
- Time-based trends in aviation incidents
- Outlier detection and handling of missing values

---

## 🧠 Machine Learning Models

The following models may be included in this project:
- Logistic Regression
- Decision Tree or Random Forest
- Support Vector Machine (SVM)
- Neural Network (optional)

### 🧪 Evaluation Metrics:
- Accuracy
- Precision, Recall
- F1-Score
- Confusion Matrix
- ROC-AUC (optional)

---

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/air-crash-severity-prediction.git
   cd air-crash-severity-prediction
