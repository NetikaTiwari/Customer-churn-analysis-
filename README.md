# 📞 Telecom Customer Churn Analysis

This project presents an in-depth **exploratory data analysis (EDA)** of a telecom company's customer data to understand the factors that contribute to **customer churn**. The goal is to uncover insights, visualize trends, and identify key reasons why customers leave the service.

## 📌 Objective

To analyze telecom customer behavior and detect patterns associated with churn using data visualization and basic machine learning techniques.

## 🧠 Key Questions Explored

- What percentage of customers are churning?
- Which services are most linked with churn?
- Do contract types or monthly charges affect churn?
- Are long-term customers more loyal?

## 📊 Dataset Information

- **Source**: Telecom customer dataset
- **Rows**: ~7,000 customers
- **Columns**: Customer demographics, account info, services used, and churn label

### Key Features:
- `gender`, `SeniorCitizen`, `Partner`, `Dependents`
- `tenure`, `PhoneService`, `InternetService`, `Contract`
- `MonthlyCharges`, `TotalCharges`, `Churn`

## 🔍 EDA Process

1. **Data Cleaning**
   - Handled missing and invalid values in `TotalCharges`
   - Converted columns to correct datatypes

2. **Data Visualization**
   - Pie chart: Overall churn rate
   - Count plots: Churn vs Contract/Payment Method/Internet Service
   - Box plots: Monthly Charges & Tenure by Churn
   - Heatmap: Correlation matrix

3. **Key Observations**
   - Month-to-month contract users churn more
   - High `MonthlyCharges` → higher churn
   - Customers with fiber optic internet show higher churn
   - Long-tenure customers are less likely to churn

## 🔢 Optional ML Model (if included)

- Model Used: Logistic Regression / Random Forest
- Train-Test Split
- Accuracy and confusion matrix shown

## 📈 Tools & Libraries

- Python
- Jupyter Notebook
- Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

## 🚀 How to Run

1. Clone this repository or download the notebook
2. Install the requirements:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
