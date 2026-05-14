# 📊 Power BI End-to-End Telecom Churn Analysis

## 🔍 Project Overview
This project builds a complete **ETL pipeline + analytical dashboard + churn prediction model** to analyze telecom customer behavior and reduce churn.

The objective is to transform raw customer data into **actionable business insights** and identify customers at high risk of leaving.

---

## 🎯 Project Goals

- Build an end-to-end ETL pipeline using SQL  
- Analyze customer data across multiple dimensions  
- Identify churn patterns and high-risk segments  
- Recommend targeted retention strategies  
- Predict future churners using machine learning  

---

## 🏗️ Data Pipeline Architecture

```
Raw Data (CSV)
      ↓
SQL (Data Cleaning & Transformation)
      ↓
Structured Tables
      ↓
Power BI (Data Modeling + DAX)
      ↓
Dashboard & Insights
      ↓
ML Model (Random Forest)
```

---

## 📊 Key Metrics

- **Total Customers**
- **Total Churn**
- **Churn Rate (~17.5%)**
- **New Joiners**

---

## 📈 Dashboard Analysis

### 🔹 Customer Segmentation
- Demographic (Gender, Age)
- Geographic (if available)
- Payment & Account Info
- Services subscribed

### 🔹 Behavioral Analysis
- Tenure vs Churn
- Monthly Charges impact
- Service usage patterns

---

## 🧠 Key Insights

### 📉 Overall Churn
- Approximately **17.5% of customers have churned**, indicating a significant retention challenge  

---

### 👥 Demographic Trends
- **64% of churned customers are female**  
- Within this group, **31.5% are above 50 years of age**  
- The **50+ age group is the largest customer segment (2,838 customers)**  

👉 Indicates a strong need for **age-specific retention strategies**

---

### 🏢 Competitor Impact
- **496 customers churned due to competitors**  
  - 183 left for **better offers**  
  - 180 left for **better devices**  

👉 Pricing and device offerings are major competitive gaps  

---

### ⚠️ Service Quality Issues
Customers using the following services show higher churn:
- Internet Service  
- Paperless Billing  
- Phone Services  
- Unlimited Data  

👉 Suggests **service quality or experience issues**  

---

### 🔗 Lack of Engagement (Hidden Risk)
Customers NOT using value-added services are also more likely to churn:
- Device Protection  
- Online Backup  
- Online Security  
- Premium Support  
- Streaming Music  

👉 These services act as **retention drivers ("stickiness")**  

---

## 🔮 Churn Prediction

A **Random Forest model** was applied to predict future churners:

- Identified **378 high-risk customers** from new joiners dataset  

👉 Enables **proactive retention campaigns**

---

## 💡 Business Recommendations

### 🎯 Retention Strategies
- Target **female customers (50+)** with personalized offers  
- Improve onboarding for **new customers**  
- Provide incentives for **long-term contracts**  

### 🏢 Competitive Strategy
- Introduce **better pricing plans**  
- Upgrade **device offerings**  

### 🛠️ Service Improvements
- Improve quality of **internet and phone services**  
- Fix friction in **paperless billing experience**  

### 🔗 Engagement Strategy
- Bundle **value-added services**  
- Promote **security & support features**  

---

## 📷 Dashboard Preview

_Add screenshots in /images folder_

---

## 🛠️ Tools & Technologies

- SQL (ETL pipeline)
- Power BI (Dashboard & Data Modeling)
- DAX (KPIs & calculations)
- Python (Random Forest Model)
- Excel (Initial exploration)

---

## 🚀 How to Use

1. Open `/pbix/churn_analysis.pbix`  
2. Explore filters and visuals  
3. Analyze churn drivers interactively  

---

## 📂 Resources 
- Live Report: [[Churn Analysis](https://app.powerbi.com/view?r=eyJrIjoiODIwZWJkOTktODVlZS00Y2YzLThkNzYtNmIzYzE4NDFjOGRlIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)]
