# 📊 Loan Performance Data Insights

## 📍 Project Overview  
This project analyzes **Fannie Mae’s Single-Family Loan Performance Data**, a comprehensive dataset tracking **mortgage loan performance, delinquency trends, and risk factors** in the U.S. housing market. The dataset includes **loan-level acquisition data and monthly performance data** spanning from **2000 to 2023**.  

Using **PySpark in Google Colab**, this project investigates **credit risk, loan delinquency rates, and default trends** to provide **data-driven insights** for **lenders, investors, and policymakers**.

---

## 🔑 Key Insights  

### 1️⃣ **Credit Score & Loan Performance Analysis**  
- **Average FICO Score Comparison**:  
  - Compared **average FICO scores** for loans from **two assigned years** to identify **credit quality trends**.  
  - Noted fluctuations in **borrower creditworthiness over time**.  

- **Distribution of Credit Scores by Loan Status**:  
  - **Performing loans** had **higher FICO scores**, while **defaulted loans** had lower scores.  

### 2️⃣ **Loan Delinquency & Default Trends**  
- **Delinquency Rates (30, 60, 90 days past due)**:  
  - Analyzed **monthly delinquency patterns** and how they vary by **loan term & interest rates**.  
  - **Higher delinquency rates in subprime loans** (low FICO & high LTV).  

- **Default Risk by Loan Origination Year**:  
  - Compared **default rates across different quarters** to assess **risk trends over time**.  
  - Found **higher default rates in economic downturns** (e.g., 2008 financial crisis).  

### 3️⃣ **Correlation Analysis & Market Trends**  
- **FICO Score vs. Loan-to-Value (LTV) Ratio vs. Interest Rates**:  
  - Strong correlation between **low FICO scores, high LTV, and increased risk of delinquency**.  
  - **Higher interest rates correlated with higher default probabilities**.  

- **Loan Modifications & Recovery After Default**:  
  - Analyzed **foreclosure recovery rates**, measuring **the percentage of loan amounts recovered** after default.  

- **Property Price Trends**:  
  - **Plotted average, median, and variance of property prices** over time, bucketed by month.  
  - **Observed price appreciation trends & fluctuations in property values.**  

---

## 🔧 **Technical Implementation**  

### 📥 **Data Processing & Cleaning**  
- **Loaded Acquisition & Performance data in PySpark** for efficient processing.  
- **Converted CSV to Parquet** for optimized querying and analysis.  
- **Performed feature engineering** on credit scores, LTV, interest rates, and loan delinquency trends.  

### 📊 **Exploratory Data Analysis (EDA)**  
- **Visualized delinquency & default trends** using **bar charts, stacked plots, and histograms**.  
- **Correlation matrix & statistical analysis** to evaluate relationships between **FICO, LTV, interest rates, and loan outcomes**.  

### 🤖 **Predictive Modeling & Forecasting**  
- **Machine Learning Models (Regression & Classification)**:  
  - Developed **logistic regression models** to classify loans as **performing or delinquent** based on borrower & loan features.  
  - Used **time-series analysis** to track **delinquency rate trends over quarters**.  

---

## 🚀 **Key Business Applications**  
✅ **Credit Risk Assessment**: Identify borrowers with higher default risks based on FICO & LTV.  
✅ **Loan Portfolio Optimization**: Improve loan approval strategies using predictive analytics.  
✅ **Housing Market Trends**: Analyze **property price fluctuations & loan performance variations**.  
✅ **Lender Decision-Making**: Use data insights to design **better mortgage lending policies**.  

---

## 📂 **Repository Structure**  

📂 Loan-Performance-Data-Insights  
├── 📂 data/                # Raw & processed Fannie Mae loan data  
├── 📂 notebooks/           # Google Colab notebooks  
├── 📂 models/              # Trained ML models for loan default risk  
├── 📂 visualizations/      # Charts, reports & analysis outputs  
├── README.md              # Project summary & key insights  
├── requirements.txt       # Dependencies (PySpark, Pandas, MLlib, Sklearn)  
└── LICENSE                # Open-source license  

