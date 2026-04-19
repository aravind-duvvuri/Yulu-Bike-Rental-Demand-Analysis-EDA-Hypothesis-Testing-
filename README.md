# 🚲 Yulu Bike Rental Demand Analysis

## 📌 Overview
This project analyzes bike rental demand data from Yulu to understand how factors like weather, season, and working days impact usage. It combines exploratory data analysis with statistical hypothesis testing.

---

## 📊 Dataset
- ~10,886 records
- Features include:
  - Datetime, Season, Holiday, Working Day
  - Weather, Temperature, Humidity, Windspeed
  - Casual, Registered, Total Rentals

---

## 🧠 Problem Statement
- What factors influence bike rental demand?  
- Does weather or season significantly impact usage?  
- Is there a difference between casual and registered users?  

---

## 🔧 Approach

### 1. Data Cleaning & Preparation
- Converted datetime column to proper format  
- Treated categorical variables appropriately  
- Verified absence of missing and duplicate values  

### 2. Exploratory Data Analysis
- Analyzed distributions of weather, season, and working days  
- Studied usage patterns across casual and registered users  
- Identified skewness and demand spikes in rental data  

### 3. Statistical Analysis
- Applied hypothesis testing (t-test, ANOVA, chi-square tests)  
- Evaluated impact of weather, season, and working days on demand  
- Tested statistical significance of observed differences  

---

## 📈 Key Insights
- Bike usage is significantly higher on working days, indicating commuter-driven demand  
- Weather conditions strongly influence rentals, with clear weather leading to higher usage  
- Registered users contribute more consistently to total demand compared to casual users  
- Demand shows variability based on season and environmental factors  

---

## 🛠️ Tools & Technologies
- Python (Pandas, NumPy)  
- Matplotlib, Seaborn  
- Scipy (Hypothesis Testing)  

---

## 🚀 Conclusion
The analysis demonstrates that environmental and temporal factors significantly impact bike rental demand, providing insights for operational planning and demand forecasting.

---

## 📁 Project Structure
- `yulu_analysis.ipynb`

---

## 📬 Author
Aravind Duvvuri
