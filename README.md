# 📊 Customer Churn Analysis using EDA

## 📌 Project Overview
This project performs Exploratory Data Analysis (EDA) on a Netflix-like customer dataset to understand factors influencing customer churn. The goal is to identify patterns in user behavior and provide insights that help improve customer retention.

---

## 🎯 Objectives
- Analyze customer data to understand churn behavior  
- Identify key features affecting churn  
- Visualize relationships between variables  
- Generate actionable insights  

---

## 📂 Dataset
The dataset contains customer information such as:

- `customer_id` – Unique identifier  
- `subscription_type` – Type of plan  
- `monthly_fee` – Subscription cost  
- `watch_hours` – Total usage  
- `avg_watch_time_per_day` – Engagement metric  
- `device_type` – Platform used  
- `churn` – Target variable (Yes/No)  

---

## 🛠️ Tools & Technologies
- Python  
- Google Colab  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  

---

## ⚙️ Project Workflow

### 1. Data Loading
- Imported dataset into Pandas DataFrame  

### 2. Data Cleaning
- Removed unnecessary columns (`customer_id`)  
- Handled missing values  
- Converted target variable (`churn`) into numeric  

### 3. Data Preprocessing
- Converted numerical features into categorical bins using `pd.cut()`  
- Prepared data for visualization  

### 4. Exploratory Data Analysis

#### 🔹 Univariate Analysis
- Distribution of numerical features  
- Frequency of categorical features  

#### 🔹 Bivariate Analysis
- Used countplots to analyze feature vs churn relationships  

#### 🔹 Correlation Analysis
- Heatmap to identify relationships between variables  

---

## 📊 Key Visualizations
- Churn distribution plot  
- Countplots (categorical vs churn)  
- Binned numerical feature plots  
- Correlation heatmap  

---

## 🔍 Key Insights
- Customers with **low watch hours** are more likely to churn  
- Higher **monthly fees** increase churn probability  
- Certain **subscription types** have higher churn rates  
- High engagement reduces churn risk  

---

## 📈 Conclusion
EDA revealed that customer churn is mainly influenced by **engagement, pricing, and subscription type**. These insights can help businesses design better retention strategies and improve user experience.

---

## 🚀 Future Scope
- Apply machine learning models (Logistic Regression, Random Forest)  
- Handle class imbalance  
- Build a churn prediction system  
- Develop interactive dashboards  

---

## ▶️ How to Run
1. Open the notebook in Google Colab  
2. Upload the dataset  
3. Run all cells step by step  


---

## ⭐ Project Status
✅ Completed (EDA Phase)
