# Credit-Score-Prediction_202401100400166 

## Overview
This project builds a **Credit Score Prediction Model** using machine learning techniques. The dataset consists of financial attributes such as **Age, Income, Loan Amount, Credit History, Marital Status**, and predicts whether a **Loan is Approved**.

## Features Used
- **Age** (18-70 years)
- **Income** (Monthly earnings)
- **Loan Amount** (Requested loan amount)
- **Credit History** (Length of credit history in months)
- **Marital Status** (0 = Single, 1 = Married)
- **Loan Approved** (Target variable: 0 = Not Approved, 1 = Approved)

## Steps to Run the Code
1. Install dependencies:  
   ```sh
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
2. Run the Python script to generate and analyze the dataset.
   ```sh
   python credit_score_prediction.py
   ```
3. The script will:
   - Generate a dummy dataset
   - Preprocess data (scaling & splitting)
   - Train a **Random Forest Classifier**
   - Evaluate model accuracy
   - Display visualizations (Feature distributions, Loan approval rate, Correlation heatmap, Confusion matrix, Feature importance)

## Visualizations
The script generates the following:
- **Data Distribution** (Histograms)
- **Loan Approval Rate** (Pie Chart)
- **Feature Correlation** (Heatmap)
- **Confusion Matrix** (Model performance)
- **Feature Importance** (Bar Chart)

## Expected Output
The final output includes:
1. **Model Accuracy & Classification Report**
2. **Charts & Graphs for Data Understanding**
3. **PDF Report (Title Page, Introduction, Methodology, Code, Screenshots)**

## License
This project is open-source and available for modification and enhancement. Feel free to contribute!

---
### 🚀 Happy Learning & Predicting!

