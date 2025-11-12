# 💻 Laptop Price Prediction

This project predicts the **price of a laptop** based on its specifications using **Machine Learning (Ridge Regression)**.  
It uses a combination of **data preprocessing**, **encoding**, and **regression modeling** to estimate prices with good accuracy.

---

## 📂 Project Overview

The project includes:
- Data preprocessing (handling categorical and numerical columns)
- Encoding categorical variables using `OneHotEncoder`
- Applying a **Ridge Regression** model
- Evaluating model performance using **R² score** and **Mean Absolute Error (MAE)**

---

## ⚙️ Tech Stack

- **Language:** Python  
- **Libraries:**
  - pandas
  - numpy
  - scikit-learn
  - matplotlib / seaborn (for visualization)

---

## 🧠 ML Workflow

### 1. Data Preprocessing
- Load and clean dataset
- Encode categorical columns with `OneHotEncoder(sparse_output=False, drop='first')`
- Standardize numerical columns
- Combine all features using `ColumnTransformer`

### 2. Model Building
- Model used: **Ridge Regression**
- Regularization parameter: `alpha = 10`
- Training using `Pipeline` for end-to-end transformation and prediction

### 3. Evaluation
- Metrics:
  - R² Score
  - Mean Absolute Error (MAE)

---

## 📊 Results

| Metric | Score |
|---------|-------|
| R² Score | ~0.85 |
| MAE | ~0.12 |

*(Values may vary based on dataset split and tuning)*

---

## 🚀 How to Run

1. Clone this repository  
   ```bash
   git clone https://github.com/<your-username>/Laptop_Price_Prediction.git
   cd Laptop_Price_Prediction
