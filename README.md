# Customer Churn Retention

## 📌 Project Overview
The **Customer Churn Retention** project focuses on identifying customers likely to discontinue services and providing actionable insights to reduce churn. Using Python, Machine Learning, and Power BI, this project analyzes customer behavior patterns and builds predictive models to support data-driven retention strategies.

---

## 🎯 Business Objectives
- **Churn Prediction:** Identify customers who are likely to leave.
- **Customer Retention:** Develop targeted retention strategies for at-risk customers.
- **Revenue Optimization:** Reduce customer loss to improve profitability.
- **Customer Segmentation:** Group customers by churn risk and behavioral patterns.
- **Data-Driven Decision Making:** Enable management to take strategic actions using insights.

---

## 📂 Dataset
**Dataset Name:** WA_Fn-UseC_-Telco-Customer-Churn  
**Source:** Telco Customer Churn (public dataset)

### Key Fields
- `CustomerID` – Unique identifier  
- `Gender`, `SeniorCitizen`, `Partner`, `Dependents`  
- `Tenure` – Months stayed with the company  
- `InternetService` – DSL / Fiber / None  
- `Contract` – Month-to-month / One year / Two years  
- `MonthlyCharges`, `TotalCharges`  
- `Churn` – (Yes/No)

This dataset captures customer demographics, account information, and usage patterns helpful for churn prediction.

---

## 🛠️ Technology Stack
- **Python:** Pandas, NumPy, Scikit-learn, Matplotlib  
- **Jupyter Notebook:** Model building & experimentation  
- **Power BI:** Dashboard & visualization  

---

## 📊 Analysis & Key Visualizations

### **1. Churn Distribution**
- **Chart:** Donut/Pie  
- **Insight:** Shows percentage of customers lost vs retained.

### **2. Monthly Charges vs Churn**
- **Chart:** Clustered Column  
- **Insight:** Identifies price-sensitive segments.

### **3. Contract Type vs Churn**
- **Chart:** Bar Chart  
- **Insight:** Month-to-month contracts show significantly higher churn.

### **4. Tenure vs Churn**
- **Chart:** Line Chart  
- **Insight:** New customers with low tenure churn more often.

### **KPIs Included**
- Churn Rate  
- Retention Rate  
- Average Tenure  
- Monthly Charges Impact  
- Model Accuracy Score  

---

## 🧪 Methodology

### **1. Data Preprocessing**
- Missing value treatment  
- Converting `TotalCharges` to numeric  
- Encoding categorical variables  
- Scaling numerical fields  
- Handling class imbalance (e.g., SMOTE)  
- Train-test split with stratification  

### **2. Exploratory Data Analysis**
- Univariate & bivariate analysis  
- Correlation heatmaps  
- Churn behavior comparison across demographics and contract types  

### **3. Model Building**
Models used:
- Logistic Regression  
- Random Forest  
- Decision Tree  
- XGBoost / LightGBM  

Evaluation metrics:
- Accuracy  
- Precision, Recall, F1-score  
- ROC-AUC  
- Confusion Matrix  

---

## 📈 Power BI Dashboard
The Power BI dashboard includes:

- Churn vs Retention Overview  
- Customer Segmentation  
- Monthly Charge & Tenure Impact  
- Contract-wise Churn Rate  
- ML Prediction Insights  
- Feature Importance View  

This helps management visually interpret churn drivers and customer risk groups.

---

## ✅ Conclusion & Recommendations
- Customers on **month-to-month contracts** are at the highest churn risk—offer loyalty benefits or upgrade offers.
- Customers with **high monthly charges** are more likely to churn—consider discounts or bundled packages.
- **Newly joined customers (low tenure)** should be targeted with onboarding engagement programs.
- ML predictions help create prioritized retention lists for proactive customer support.

---

## 📁 Project Structure
