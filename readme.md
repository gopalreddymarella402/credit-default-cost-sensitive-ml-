# 💳 Credit Default Prediction using Cost-Sensitive Machine Learning

## 📖 Project Overview
This project focuses on predicting credit card defaults using machine learning techniques, with a strong emphasis on reducing financial risk through cost-sensitive learning.

Traditional models optimize for accuracy, but in real-world banking, missing a defaulter is much more costly than incorrectly flagging a non-defaulter. This project addresses that gap.

## 🎯 Objectives
- Predict credit default accurately
- Handle class imbalance effectively
- Minimize financial loss using cost-sensitive learning
- Compare baseline vs advanced models

## 📊 Dataset
- Source: UCI Machine Learning Repository
- Records: 30,000 customers
- Country: Taiwan
- Year: 2005
- Target: Default payment next month

## ⚙️ Models Used
- Logistic Regression (Baseline)
- Random Forest
- XGBoost
- Cost-Sensitive Learning (Class Weights)


## 📈 Key Results
- Baseline Recall: **24.3%**
- Cost-Sensitive Recall: **61.6%**
- Financial Cost Reduced:
  - From ₹10.18M → ₹4.66M

## 🔍 Key Insights
- PAY_0 is the most important feature
- Behavioural features outperform demographic features
- Threshold tuning significantly reduces cost

## 📂 Repository Structure
data/ → Dataset
notebooks/ → Jupyter Notebook
reports/ → Final Report
presentation/ → PPT



## 🚀 How to Run
1. Install dependencies:
   pip install pandas numpy scikit-learn xgboost shap matplotlib seaborn
2. Open notebook:
   Jupyter Notebook



## 👨‍💻 Author
**Gopal Reddy Marella**

## 🔗 GitHub Link

https://github.com/gopalreddymarella402/credit-default-cost-sensitive-ml/
