# Analyzing-the-Drivers-of-Nasdaq-Returns-From-The-Magnificent-7-and-Macroeconomic-Indicators
This quantitative analysis investigates the drivers of daily Nasdaq Composite returns. It answers a key question: Are tech market movements primarily fueled by tech giants (The Magnificent 7) or are they dictated by global economic conditions and investor sentiment?

### Variables
* Magnificent 7 Stock In Nasdaq (AAPL,MSFT,AMZN,NVDA,GOOGL,TLSA,META)
* Alternative Assets (COMEX,WTI)
* Important Index (VIX,USD index,Treasury infiation)

### Target Variable
* Nasdaq Composite Index

Resources: https://finance.yahoo.com/   &  https://www.nasdaq.com/

## Analysis Process

### First step : Extrace Data From Nasdaq (By yfinance)
1) Extrace Data (Previous 5 Years)
2) Save Data to CSV
3) Exporatory Data Analysis To Checking Data Distrlbution & Data Belvoir
4) Cleansing Data (Missing , Outlier , Datetime)
5) Add Feature Engineering (By Chance raw price to Return Percentage Per Day)
6) Save Cleaned & Return Data

### Second step : Analysis by Multiple Regression
1) Descriptive Analysis
* Find Describe Statistics From Assets & Index
* Explore Cummulative From Return Rate
* Explore Return Distribution & Return Volatility
* Visualize Growp Rate & Risk-Adjusted Return

2) Diagnotic Analysis
* Find Correlation
* Linearity Checking
* Visualize Scatter plot Correlation & Correlation heat map

3) Predictive Analysis (Using Both Stat model and Machine Learning)
* Train Data & Modeling
* Before Test : VIF Checking
* Test & Summary Model
* Predict Model with β (Beta)
* Model Evaluation
* Find MLR Coefficients (Impact Insight)
* Visualize Model And Data Insight
* Save Data Predict Flie as CSV

### Third step : Visualization (Using Power BI)

1) Create Fundamentals Page (For Descriptive Analysis Data)
2) Create MLR Page (For Predictive Analysis Model)
3) Create Alternative Page (For Compare Analyze what already exists compared to ours.)
* Alternative Data has Using The Geopolitical Risk Dashboard from BlackRock Investment Institute

Resources: https://www.blackrock.com/corporate/insights/blackrock-investment-institute/interactive-charts/geopolitical-risk-dashboard

### Final step : Summary result  

Dashboard : https://drive.google.com/file/d/1Ck9JT_TzA2ufGL-w75SkVDssVZOLhJQ7/view?usp=sharing  
Slide : https://drive.google.com/file/d/1KfS3Hh-Qkp-C7do7-9tjEYOtWq4rkDhN/view?usp=drive_link
