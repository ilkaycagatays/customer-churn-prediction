# 🔄 Customer Churn Prediction

## 📌 About the Project
Predicting customer churn for a telecom company using Machine Learning.
The goal is to identify customers likely to leave before they actually do.

## 📊 Dataset
- **Source:** Telco Customer Churn (Kaggle)
- **Size:** 7,043 customers, 21 features
- **Target:** Churn (Yes/No)

## 🛠️ Technologies Used
- Python, Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

## 🤖 Models
| Model | Accuracy |
|-------|----------|
| Logistic Regression | 78.75% |
| Random Forest | 79.25% |

## 💡 Key Findings
- **New customers (0-5 months)** churn the most → retention program needed
- **High monthly charges** increase churn risk significantly
- **TotalCharges, MonthlyCharges, tenure** are the top 3 most important features
- Customers on **long-term contracts** are less likely to churn

## 📁 Project Structure
```
customer-churn-prediction/
 ├── data/
 ├── notebooks/
 ├── models/
 └── README.md
```
