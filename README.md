# Logistic Regression Classification on Diabetes Datasets

This project applies **Logistic Regression** to two diabetes datasets:
- **UCI Diabetes dataset** (`uci_diabetes.csv`)
- **Pima Indians Diabetes dataset** (`pmi_diabetes.csv`)

## 📌 Features
- Load datasets using **Pandas**
- Select features:
  - Glucose
  - BloodPressure
  - BMI
- Target variable:
  - Outcome (indicating diabetes presence)
- Perform classification analysis:
  - Train/test split (80/20)
  - Fit logistic regression model
  - Predict diabetes outcome
  - Evaluate model performance using:
    - Accuracy
    - Precision
    - Recall
    - F1 Score
- Visualize confusion matrices for both datasets using **Seaborn heatmaps**

## 🚀 Usage
1. Place `uci_diabetes.csv` and `pmi_diabetes.csv` in the project directory.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
