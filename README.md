# Bitcoin-Historical-Market-AnalysisDashboard-POWER-BI
**(Power BI | Time Series Analysis | Financial Data Modeling)**

![ADEDIRANbitcoinHistoricalPOWERBIdashboard](https://github.com/user-attachments/assets/20a4bcb6-affa-4aec-b6ec-0273419d6cf3)

# 📊 Bitcoin Historical Market Analysis Dashboard  

**Power BI | Time Series Analysis | Financial Data Modeling**  

---

## 🚀 Project Overview

This project analyzes historical Bitcoin trading data from **January 2012 to March 2021** using minute-level market data from Bitstamp.  

The objective was to transform raw, high-frequency cryptocurrency trading records into an executive-level analytical dashboard using Power BI.

The final output delivers aggregated insights on:

- Price behavior  
- Trading volume growth  
- Volatility patterns  
- Long-term market cycles  

---

## 🎯 Business Problem

Cryptocurrency datasets contain millions of minute-level records. Extracting strategic insight requires structured aggregation and financial modeling.

### Core Challenge

How do you convert high-frequency Bitcoin trading data into meaningful year-over-year insights that reveal long-term market behavior?

### Key Analytical Questions

- How has Bitcoin’s price evolved over time?  
- Which years show significant growth cycles?  
- How do trading volumes relate to price movement?  
- What volatility patterns exist between Open and Close prices?  

---

## 📂 Dataset Information

- **Source:** Bitstamp USD Historical Data  
- **Granularity:** 1-minute trading data  
- **Timeframe:** 2012-01-01 to 2021-03-31  

### Columns Included

- Timestamp (Unix)  
- Open  
- High  
- Low  
- Close  
- Volume BTC  
- Volume USD  
- Weighted Price  

---

## 🛠 Data Processing

### 1️⃣ Cleaning

- Converted Unix timestamp to DateTime  
- Removed null values  
- Validated numerical fields  

### 2️⃣ Feature Engineering

- Extracted Year and Month  
- Created aggregated financial KPIs using DAX  

### 3️⃣ Aggregation

- Reduced minute-level data to yearly summaries  
- Structured time-series model  

---

## 🧮 Data Model

Single fact table with derived time attributes.

### Key Calculated Measures

- Total Volume BTC  
- Total Currency Volume  
- Average Weighted Price  
- Sum of High and Low  
- Yearly Open vs Close comparison  

---

## 📊 Dashboard Features

### KPI Cards

- Adjusted Closing Stock: **3.31M**  
- Currency Volume: **25.01bn**  
- Volume BTC: **3.31M**  
- Weighted Price: **2.72bn**  

### Visual Components

- High vs Low by Year  
- Volume BTC Trend Line  
- Currency Volume Area Chart  
- Weighted Price Distribution Donut  
- Open vs Close Comparison Bar Chart  
- Month Filter Slicer  

---

## 📈 Key Insights

- Significant volume growth occurred after 2016  
- 2017 and 2020 show major bull market cycles  
- Volume spikes correlate strongly with price acceleration  
- Weighted price concentration increases sharply in later years  
- Volatility widens during rapid growth periods  

---

## 🧰 Tools Used

- Power BI  
- Power Query  
- DAX  
- Excel  
- CSV Data Source  

---

## 🧠 Analytical Approach

### Data Cleaning  
Validated raw dataset and ensured structural consistency.

### Feature Engineering  
Built time attributes and financial KPIs.

### Aggregation  
Converted minute-level data into yearly analytical summaries.

### Visualization  
Designed executive-ready KPI dashboard with comparative analysis.

### Validation  
Cross-checked totals against the raw dataset.

---

## 💼 Business Value

This project demonstrates how raw financial transaction data can be converted into structured insights for:

- Investment analysis  
- Market trend evaluation  
- Volatility assessment  
- Strategic forecasting  

It highlights the importance of:

- Time-based aggregation  
- Volume-price relationship analysis  
- Executive-focused visualization  

---

## 🔮 Future Improvements

- Add Year-over-Year growth percentages  
- Include moving averages  
- Integrate volatility index  
- Build predictive forecasting model  
- Introduce correlation matrix  

---

## ▶️ How to Use

1. Download the `.pbit` Power BI template  
2. Connect to the CSV dataset  
3. Refresh the model  
4. Interact with the dashboard using the Month slicer  

---

## 📌 Author

Ajibola Odutola  
Marketing Data Analyst | Business Intelligence Specialist
"""
