# 📊 Product Sales Forecast - Time Series Forecasting
SQL | Python | Data Manipulation | Forecasting | Machine Learning

## 🔍 Project Overview
This project focuses on **forecasting product sales** using a combination of **time series models and causal models**. The dataset contains **historical sales records** from **10 stores and 50 products**, spanning **2013 to 2017**. The goal is to **develop a reliable forecasting model** to predict sales trends, which can help businesses optimize inventory, improve demand planning, and maximize revenue.

## 🎯 Key Objectives
- Analyze sales data for trends, seasonality, and patterns.
- Apply **time series forecasting techniques** to predict future sales.
- Compare various forecasting models and select the best-performing one.
- Provide **data-driven insights** to optimize business decision-making.

## 📈 Models Implemented
The project explores multiple forecasting techniques to determine the most **accurate** and **scalable** model:

### **1️⃣ Time Series Forecasting Models**
- **📌 Seasonal Naive Model** → Uses last year’s sales as a baseline.
- **📌 Holt-Winters Model (Triple Exponential Smoothing)** → Captures trend & seasonality.
- **📌 ARIMA (AutoRegressive Integrated Moving Average)** → Captures trends & autoregressive patterns.
- **📌 SARIMA (Seasonal ARIMA)** → ARIMA with a seasonal component.

### **2️⃣ Causal Model (Supervised Machine Learning)**
- **📌 Linear Regression** → Predicts sales using engineered features such as past sales, rolling averages, and seasonal factors.

## 🔬 Methodology
### 1. **Data Preprocessing**
   - Handled missing values, removed outliers, and converted dates to a structured format.
   - Created **new features** (lag variables, rolling averages) for improved forecasting.

### 2. **Exploratory Data Analysis (EDA)**
   - Identified **seasonality** (monthly trends, peak sales periods).
   - Visualized **yearly and weekly sales patterns** for data-driven insights.

### 3. **Model Selection & Performance Evaluation**
   - **MAPE (Mean Absolute Percentage Error)** was used as the key evaluation metric.
   - Compared the **performance of different models** to find the best fit.

## 🔑 Key Insights & Business Impact
- **📊 Seasonality Trends**: Sales consistently **increase mid-year**, peaking in **July**, followed by a drop in **December**.
- **🏆 Best Performing Model**: **Linear Regression outperformed** all other models, achieving a **MAPE of 19.9%**, making it the best model for sales forecasting.
- **📦 Inventory Optimization**: The model can be **used to forecast demand**, reducing **overstocking and stockouts**.
- **💰 Revenue Maximization**: Businesses can **adjust pricing and marketing efforts** based on predicted sales trends.

## 🛠️ Technologies Used
- **Python** → Data processing & modeling  
- **Pandas, NumPy** → Data manipulation  
- **Matplotlib, Seaborn** → Data visualization  
- **Statsmodels, Scikit-learn** → Forecasting & machine learning  

## ✅ Why This Project is Relevant for Business?
This project showcases **data-driven decision-making in sales forecasting**. It demonstrates:
- **How to leverage historical data to predict future sales trends**.
- **The impact of different forecasting techniques on business strategy**.
- **The importance of evaluating multiple models to ensure optimal performance**.

## 📌 Final Takeaway
By leveraging **Linear Regression and Time Series Models**, businesses can **accurately forecast sales**, **optimize inventory**, and **enhance profitability**. This project provides a **scalable solution** for **demand forecasting**, which can be applied across various industries.

---

### 🚀 **Interested in similar projects?**
Connect with me on **[LinkedIn](https://www.linkedin.com/in/abhinavsahu2604/)** or explore my **GitHub portfolio** for more **data-driven solutions**.

