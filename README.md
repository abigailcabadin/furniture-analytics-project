# 🪑 Furniture Analytics Project

A full-stack data analytics project exploring delivery performance, customer satisfaction, and profitability for a fictional online furniture retailer. This project combines **R-based data cleaning, exploration, and predictive modeling** with a **multi-page Power BI dashboard** to deliver actionable insights and strategic recommendations.

---

## 📦 Dataset

Original dataset sourced from Kaggle:  
🔗 [Online Furniture Orders, Delivery & Assembly 2025](https://www.kaggle.com/datasets/pratyushpuri/online-furniture-orders-delivery-and-assembly-2025)

Raw CSV file:  
📄 [`online_furniture_retailer.csv`](https://github.com/abigailcabadin/furniture-analytics-project/blob/main/online_furniture_retailer.csv)

Cleaned dataset (via R):  
🧼 [`furniture_data_cleaned.csv`](https://github.com/abigailcabadin/furniture-analytics-project/blob/main/furniture_data_cleaned.csv)

---

## 📈 R Markdown Analysis

Before building the dashboard, I conducted a comprehensive analysis in R using R Markdown. This report simulates the role of a **Product Quality Assurance Analyst**, uncovering inefficiencies in delivery, evaluating the impact of assembly services, and identifying drivers of customer satisfaction.

🔗 [View Full HTML Report](https://abigailcabadin.github.io/furniture-analysis-report/)

### 🔍 Key Steps in R:

#### 🧼 Data Cleaning
- Removed missing values and standardized column formats
- Validated logical consistency between service requests and cost charges
- Created new calculated fields:
  - `estimated_margin` (profit proxy)
  - `delivery_success` (binary flag)
  - `assembly_label` (for grouping service requests)

#### 📊 Exploratory Analysis
- Summary statistics across product categories and payment methods
- Distribution of customer ratings and estimated margins
- Grouped comparisons of delivery success and customer satisfaction

#### 📉 Visualizations
- Histograms of customer ratings
- Bar charts showing delivery success by category and payment method
- Margin distribution across product categories

#### 🔮 Predictive Modeling
- **Logistic Regression** to predict delivery success
- **Linear Regression** to model customer satisfaction
- **Decision Tree** and **Random Forest** to classify delivery outcomes

---

## 📊 Power BI Dashboard

Built in **Power BI**, the dashboard is divided into four key pages:

### 🔑 Key Metrics  
A high-level summary of core performance indicators  
![Key Metrics](https://raw.githubusercontent.com/abigailcabadin/furniture-analytics-project/main/Key%20Metrics.jpg)

---

### 🚚 Delivery Performance Overview  
Analyzes delivery outcomes across product categories and payment methods  
![Delivery Performance](https://raw.githubusercontent.com/abigailcabadin/furniture-analytics-project/main/Delivery%20Performance.jpg)

---

### 🌟 Customer Satisfaction Insights  
Explores customer ratings and service impact  
![Customer Satisfaction](https://raw.githubusercontent.com/abigailcabadin/furniture-analytics-project/main/Customer%20Satisfaction%20Insights.jpg)

---

### 💰 Profitability Breakdown  
Highlights margin performance across categories and services  
![Profitability Breakdown](https://raw.githubusercontent.com/abigailcabadin/furniture-analytics-project/main/Profitability%20Breakdown.jpg)
---

## 🎯 Key Insights

- **Bedroom** category leads in average margin but suffers from lower delivery success  
- **Assembly service** requests correlate with higher customer satisfaction  
- **PayPal** payments show elevated delivery failure rates  
- **Living Room** items have the highest delivery success rate  
- **Shipping cost and payment method** are strong predictors of delivery success

---

## 🛠️ Tools Used

- **R & R Markdown** for data cleaning, exploration, and modeling  
- **Power BI** for dashboard design and visualization  
- **GitHub Pages** for hosting the R Markdown report  
- **Kaggle** for dataset sourcing

---

## 💼 About Me

Hi, I’m Abigail — a data analyst passionate about turning raw data into actionable insights. This project reflects my ability to:
- Clean and transform messy datasets  
- Build predictive models and uncover patterns  
- Design intuitive, multi-page dashboards  
- Communicate findings clearly to stakeholders

Let’s connect and build something impactful together.
