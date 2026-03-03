# Bitcoin-Historical-Market-AnalysisDashboard-POWER-BI
**(Power BI | Time Series Analysis | Financial Data Modeling)**

![ADEDIRANbitcoinHistoricalPOWERBIdashboard](https://github.com/user-attachments/assets/20a4bcb6-affa-4aec-b6ec-0273419d6cf3)

**Project Overview**
This project analyzes historical Bitcoin trading data from January 2012 to March 2021 using minute-level market data from Bitstamp. The objective was to transform raw, high-frequency cryptocurrency trading records into an executive-level analytical dashboard using Power BI.
The final output delivers aggregated insights on price behavior, trading volume growth, and volatility patterns across nine years. The project demonstrates:
•	Large dataset transformation
•	Time-series aggregation
•	Financial metric modeling
•	KPI dashboard design
•	Executive storytelling through data

**Business Problem**
Cryptocurrency datasets contain millions of minute-level records, making it difficult to extract strategic insights without proper aggregation and modeling.
The core challenge addressed:
How do you convert high-frequency Bitcoin trading data into meaningful year-over-year insights that reveal long-term market behavior?
Key analytical questions:
•	How has Bitcoin’s price evolved over time?
•	Which years show significant growth cycles?
•	How do trading volumes relate to price movement?
•	What volatility patterns exist between Open and Close prices?

**Dataset Information**
Source: Bitstamp USD Historical Data
Granularity: 1-minute trading data
Timeframe: 2012-01-01 to 2021-03-31

**Data Processing**
•	Converted Unix timestamp to DateTime
•	Extracted Year and Month
•	Aggregated minute-level data to yearly summaries
•	Created financial KPIs using DAX

**Data Model**
Single fact table with derived time attributes.
Key calculated measures:
•	Total Volume BTC
•	Total Currency Volume
•	Average Weighted Price
•	Sum of High and Low
•	Yearly Open vs Close comparison

**Dashboard Features**

KPI Cards:
•	Adjusted Closing Stock: 3.31M
•	Currency Volume: 25.01bn
•	Volume BTC: 3.31M
•	Weighted Price: 2.72bn

**Visual Components:**
•	High vs Low by Year
•	Volume BTC Trend Line
•	Currency Volume Area Chart
•	Weighted Price Distribution Donut
•	Open vs Close Comparison Bar Chart
•	Month Filter Slicer

**Key Insights**
•	Significant volume growth occurred after 2016
•	2017 and 2020 show major bull market cycles
•	Volume spikes correlate strongly with price acceleration
•	Weighted price concentration increases sharply in later years
•	Volatility widens during rapid growth periods

**Tools Used**
•	Power BI
•	Power Query
•	DAX
•	Excel (initial validation)
•	CSV data source

**Analytical Approach**
1.	Data Cleaning
o	Removed null values
o	Validated numerical fields
o	Converted timestamps
2.	Feature Engineering
o	Created Year and Month columns
o	Built aggregated financial measures
3.	Aggregation
o	Reduced minute-level data to yearly metrics
o	Structured time-series model
4.	Visualization
o	Designed executive-ready KPI dashboard
o	Built comparative yearly visualizations
5.	Validation
o	Cross-checked totals against raw dataset

**Business Value**
This project demonstrates how raw financial transaction data can be converted into structured insights for:
•	Investment analysis
•	Market trend evaluation
•	Volatility assessment
•	Strategic forecasting

It highlights the importance of:
•	Time-based aggregation
•	Volume-price relationship analysis
•	Executive-focused visualization


**Future Improvements**
•	Add Year-over-Year growth percentages
•	Include moving averages
•	Integrate volatility index
•	Build predictive forecasting model
•	Introduce correlation matrix


**How to Use**
1.	Download the .pbit Power BI template
2.	Connect to the CSV dataset
3.	Refresh the model
4.	Interact with the dashboard using the Month slicer



