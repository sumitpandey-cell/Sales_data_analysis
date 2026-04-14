# 📊 Sales Data Analysis Project

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green.svg)](https://pandas.pydata.org/)
[![Tableau](https://img.shields.io/badge/Tableau-Visualization-blue.svg)](https://www.tableau.com/)

## 📋 Executive Summary

This comprehensive sales data analysis project examines regional sales performance from **2014 onwards**, providing actionable insights into revenue trends, customer behavior, product performance, and budget variance analysis. The project leverages advanced data analytics to identify key performance drivers and strategic opportunities for growth.

---

## 🎯 Project Objectives

- **📈 Analyze Sales Trends** - Track revenue and quantity patterns across years, months, and quarters
- **🌍 Geographic Performance** - Evaluate regional and state-level sales distribution
- **🛍️ Product Intelligence** - Identify top-performing products and regional preferences
- **👥 Customer Segmentation** - Score customers using RFM (Recency, Frequency, Monetary) analysis
- **💰 Budget Analysis** - Benchmark 2017 actual sales against budgeted targets
- **📊 Channel Effectiveness** - Compare performance across Wholesale, Distributor, and Export channels
- **💹 Profitability Deep Dive** - Analyze profit margins and identify high-margin opportunities

---

## 🔍 Key Business Questions Addressed

### Sales Performance Overview
- What are overall sales trends in revenue and quantity?
- How do different channels (Wholesale, Distributor, Export) contribute to total sales?
- What is the distribution of sales across regions and states?

### Product & Customer Analysis
- Which products are top-selling by revenue and quantity?
- Are there regional preferences for specific products?
- Who are the top customers by purchase value and order frequency?

### Regional Deep Dive
- Which regions consistently outperform or underperform?
- What factors explain regional performance differences?
- How do product mix and channel effectiveness vary by region?

### Budget vs. Actuals (2017)
- How did actual 2017 performance compare to budget?
- Which regions/products met or exceeded targets?
- What insights emerge from budget variances?

### Profitability Analysis
- What are average profit margins per product and order?
- Which regions and channels are most profitable?
- Where should we focus for margin optimization?

---

## 📁 Project Structure

```
Sales_data_analysis/
├── README.md                       # This file
├── Sales_data_analysis.ipynb       # Jupyter notebook with complete analysis
├── Sales Data Analysis.twbx        # Tableau workbook for interactive dashboards
├── transformed_dataset.csv         # Cleaned and merged dataset
└── data/                           # Raw data files (from Excel source)
    ├── Sales Orders
    ├── Customers
    ├── Products
    ├── Regions
    ├── State Regions
    └── 2017 Budgets
```

---

## 💾 Dataset Overview

### Key Metrics Included
| Metric | Description |
|--------|-------------|
| **Order Data** | Order numbers, dates, channels, quantities, and pricing |
| **Revenue Metrics** | Unit prices, total revenue, unit costs, and profit calculations |
| **Geographic Data** | Cities, counties, states, regions, coordinates, and demographics |
| **Customer Data** | Customer names and RFM (Recency, Frequency, Monetary) scores |
| **Product Data** | Product names and descriptions |
| **Budget Data** | 2017 budget allocations by product |
| **Demographics** | Population, household counts, median income, and area measurements |

### Time Period
- **Data Range:** 2014 - 2017+
- **Records:** Thousands of sales transactions
- **Channels:** Wholesale, Distributor, Export
- **Geographic Scope:** Multi-state US coverage

---

## 🛠️ Technologies & Tools

- **Data Processing:** Python, Pandas, NumPy
- **Analysis & Visualization:** Matplotlib, Seaborn
- **Interactive Dashboards:** Tableau
- **Notebook Environment:** Jupyter
- **Data Format:** CSV, Excel

---

## 📊 Analysis Components

### 1. Data Cleaning & Preparation
- Handling missing values and duplicates
- Data type conversions and validation
- Merging multiple data sources (Sales, Customers, Products, Regions, Budgets)

### 2. Exploratory Data Analysis (EDA)
- Sales trend visualization
- Distribution analysis by channel, region, and product
- Time-series decomposition (trends, seasonality)

### 3. Customer Analysis
- RFM scoring and segmentation
- Top customer identification
- Purchase pattern analysis

### 4. Regional Performance Analysis
- Regional revenue and profit breakdown
- State-level performance metrics
- Geographic heat mapping

### 5. Budget Variance Analysis
- 2017 actual vs. budget comparison
- Variance percentage calculation
- Performance by product and region

### 6. Profitability Analysis
- Profit margin calculations
- Cost analysis by product and channel
- Breakeven analysis

---

## 🚀 Getting Started

### Prerequisites
- Python 3.8+
- Jupyter Notebook
- Required Python libraries (see below)

### Installation

1. **Clone or download the project**
   ```bash
   cd Sales_data_analysis
   ```

2. **Install required packages**
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

3. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook Sales_data_analysis.ipynb
   ```

4. **For Tableau Dashboards**
   - Open `Sales Data Analysis.twbx` in Tableau Public or Tableau Desktop

---

## 📈 Key Findings Preview

The analysis reveals:
- **✅ Multi-channel distribution model** with varying performance characteristics
- **🎯 Clear regional performance patterns** with geographic opportunities
- **📦 Product-market fit variations** across different regions
- **💡 Budget variance insights** for resource optimization
- **📊 Profitable segments** identified for targeted growth

---

## 📊 Visualization Outputs

The project includes comprehensive visualizations:
- Time series trend charts
- Regional performance heatmaps
- Product performance rankings
- Channel comparison analysis
- Budget vs. actual variance charts
- Customer RFM distribution plots
- Profit margin analysis

---

## 🤝 How to Use This Analysis

1. **For Executives:** Review the Tableau dashboards for high-level insights and KPIs
2. **For Analysts:** Run the Jupyter notebook to deep-dive into specific metrics
3. **For Operations:** Use regional and product performance data for tactical decisions
4. **For Strategy:** Leverage budget variance and profitability insights for planning

---

## 📧 Questions & Contact

For questions, insights, or collaboration opportunities regarding this analysis:
- Review the detailed findings in the Jupyter notebook
- Explore interactive dashboards in the Tableau workbook
- Reach out for custom analysis or methodology discussion

---

## 📝 License & Attribution

This project analyzes sales data for business intelligence and strategic decision-making purposes.

---

## 🎓 Methodology Notes

- **Data Integration:** Multiple data sources merged on common keys
- **Analysis Approach:** Descriptive analytics with trend and variance analysis
- **RFM Scoring:** Weighted composite score for customer segmentation
- **Profit Calculation:** Revenue - Total Unit Cost
- **Budget Variance:** (Actual - Budget) / Budget × 100

---

**Last Updated:** April 2026  
**Status:** ✅ Active & Maintained

---

*Transform data into insights. Drive decisions with confidence.*
