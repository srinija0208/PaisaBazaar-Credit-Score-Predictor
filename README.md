# 🏦 Credit Score Classification Using Machine Learning

This project aims to predict an individual's credit score category (`Good`, `Poor`, or `Standard`) using their financial and behavioral data. The model can assist financial institutions in making informed decisions for credit approvals.

---

## 📁 Dataset

- **Source**: Paisabazaar (Banking Credit Dataset)
- **Rows**: 100,000
- **Target Column**: `Credit_Score`
- **Features**: Age, Income, Ocuupation,lLoan History, Credit Utilization, Payment Behaviour, etc.

---

## ✅ Problem Statement

To build a classification model that predicts a customer’s credit score category using various financial, demographic, and behavioral indicators.

---

## 🔧 Workflow

1. **Data Cleaning**
   - Handled missing values using median/mode imputation
   - Removed or capped outliers using IQR-based Winsorization

2. **Feature Engineering**
   - Encoded categorical features using LabelEncoder and OneHotEncoder
   - Scaled numerical features using StandardScaler
   - Label-encoded the target variable

3. **Model Building**
   - Trained and evaluated:
     - Random Forest
     - XGBoost
     - Gradient Boosting
   - Used accuracy, confusion matrix, and classification report for evaluation

---

## 📊 Model Performance

| Model             | Accuracy |
|------------------|----------|
| Random Forest     | 80.67%   |
| XGBoost           | 74.01%   |
| Gradient Boosting | 71.20%   |

- 🎯 **Best Model**: Random Forest (Balanced performance and highest accuracy)

---

## 📈 Visualizations

- Boxplots before and after Winsorization
- Confusion matrices for each model
- Bar chart comparing model accuracies

---

## 🧠 Conclusion

The Random Forest model provided the most accurate and balanced predictions for credit score classification. It can be used to assess credit risk and improve decision-making in lending operations.
