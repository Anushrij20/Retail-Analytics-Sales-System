# 🛍️ Retail Analytics & AI-Powered Sales Forecasting System


## 📎 Project Access
- GitHub Repository: [https://github.com/Anushrij20/Retail-Analytics-AI-Powered-Sales-Forecasting-System]

- Google Drive (Full Files): [https://drive.google.com/drive/folders/1uJ58FxcfzFqPnywfiq7HwGq6SPMvnKwY?usp=sharing]


## 📌 Project Overview
This project focuses on analyzing large-scale retail sales data to extract actionable business insights and predict future revenue trends. It simulates a real-world data science solution for retail decision-making.

---

## 🎯 Objectives
- Analyze sales performance across stores and product categories
- Identify seasonal patterns and revenue drivers
- Forecast future sales using time-series modeling
- Segment stores based on performance
- Present insights through an interactive dashboard

---

## 📊 Dataset Description
- Dataset: Retail Sales Data
- Time Period: Jan 2023 – Dec 2024
- Records: ~73,000
- Features include:
  - Store details (Store_ID, Location, Region)
  - Product details (Category, Subcategory, Brand)
  - Sales metrics (Units Sold, Revenue, Discounts)
  - Customer & transaction info

---

## 🧹 Data Preprocessing
- Converted Date column to datetime format
- Removed missing values and duplicates
- Created new features:
  - Year, Month, Day, Weekday
  - Weekend indicator
- Standardized column formats

---

## 📈 Exploratory Data Analysis (EDA)
- Revenue trends over time
- Monthly and seasonal sales patterns
- Store-wise performance analysis
- Product category contribution
- Regional sales comparison

---

## 🔍 Key Insights
- Certain months show consistently higher revenue, indicating strong seasonality
- A small group of stores contributes disproportionately to total revenue
- Discounts influence sales volume but do not always increase revenue

---

## 🧠 Advanced Insights
- **Revenue vs Discount Trade-off:** Higher discounts increase units sold but can reduce overall revenue, indicating the need for optimized pricing strategies.
- **Top Store Dominance:** Top-performing stores generate a large percentage of total revenue, suggesting potential for targeted expansion or replication strategies.

---

## 🤖 Machine Learning Models

### 1. Store Segmentation (Clustering)
- Algorithm: K-Means
- Features used:
  - Revenue
  - Units Sold
  - Store Rating
- Output:
  - Stores grouped into performance clusters (High, Medium, Low)

---

### 2. Sales Forecasting
- Model: Prophet
- Forecast Horizon: Next 30 days
- Captures:
  - Trend
  - Seasonality
- Output:
  - Future revenue predictions

---

## 📊 Dashboard (Power BI)
An interactive dashboard was created using :contentReference[oaicite:0]{index=0} featuring:

- Revenue trends over time
- Monthly sales distribution
- Store performance comparison
- Product category contribution
- Forecasted sales visualization
- Store cluster segmentation
- Interactive filters (Region, Store, Category)

---

## 🧰 Tools & Technologies
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn (Clustering)
- Prophet (Forecasting)
- Power BI (Dashboard Visualization)
- VS Code (Development)

---

## 📁 Project Structure


Retail-Analytics-Project/
│
├── data/
│   ├── Retail_Sales_Data_Unlox (1).csv   # Raw dataset
│   ├── cleaned_data.csv                  # Cleaned dataset after preprocessing
│   ├── forecast.csv                      # Forecasted sales output (Prophet)
│   └── store_clusters.csv                # Store segmentation output (K-Means)
│
├── notebooks/
│   └── eda.ipynb                         # Data cleaning, EDA, and modeling
│    
├── src/                                  # (Optional) Python scripts for modular code
│
├── app/                                  # (Optional) Reserved for future app deployment
│
├── README.md                             # Project documentation
│
└── .venv/                                # Virtual environment (not required in submission)



---

## ✅ Conclusion
This project demonstrates how data analytics and machine learning can be integrated to improve retail decision-making. It provides insights into sales performance and enables proactive planning through forecasting.

---

## 🚀 Future Improvements
- Incorporate external factors (festivals, weather)
- Use advanced models (LSTM)
- Deploy dashboard as a web app



> Note: The `.venv/` folder is excluded from submission as it contains environment-specific dependencies.