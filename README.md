# 🛍️ Customer Purchase Predictor

A machine learning project that predicts whether a customer will make a purchase based on demographic and behavioral data.

Built as part of my AI/data science portfolio to explore predictive modeling in a marketing context.

---

## 📊 Dataset

**Source:** [Predict Customer Purchase Behavior Dataset](https://www.kaggle.com/datasets/rabieelkharoua/predict-customer-purchase-behavior-dataset) — Kaggle  
**Size:** 1,500 customer records, 9 features

| Feature | Description |
|---|---|
| Age | Customer age |
| Gender | 0 = Female, 1 = Male |
| AnnualIncome | Yearly income in USD |
| NumberOfPurchases | Total past purchases |
| ProductCategory | Electronics, Clothing, Home, Beauty, Sports |
| TimeSpentOnWebsite | Minutes spent browsing |
| LoyaltyProgram | Whether customer is a loyalty member |
| DiscountsAvailed | Number of discounts used |
| **PurchaseStatus** | **Target — 1 = Purchase, 0 = No Purchase** |

---

## 🤖 Model

- **Algorithm:** Random Forest Classifier
- **Train/Test Split:** 80/20
- **Accuracy:** ~95%

---

## 📈 What's Inside the Notebook

- Exploratory data analysis with visualizations
- Feature correlation heatmap
- Model training and evaluation
- Confusion matrix
- Feature importance breakdown — identifying what actually drives purchase decisions

---

## 🛠️ Tools Used

- Python
- pandas, numpy
- scikit-learn
- matplotlib, seaborn
- Google Colab

---

## 🔍 Key Finding

Time spent on website and loyalty program membership were the strongest predictors of whether a customer would make a purchase.
