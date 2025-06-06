# GIVA Business Analytics Dashboard

A comprehensive business intelligence analysis of GIVA's e-commerce performance data from July to November 2022, featuring advanced Excel analytics, forecasting models, and data visualization.

## Sample Dashboard Screenshot

![Business-analyst-excel-task-](images/Sample_data.png)


## 📊 Project Overview

This project analyzes GIVA's business metrics across multiple dimensions including sales performance, user engagement, conversion rates, and growth patterns. The analysis spans 143 days of operational data and provides actionable insights for business optimization.

## 🔍 Key Metrics Analyzed

- **Daily Active Users (DAU)**
- **Order Performance** (Overall Orders, Return Orders, Net Orders)
- **Revenue Metrics** (Net Sales, Average Order Value)
- **User Acquisition** (New Installs, Sign-up Rates)
- **Conversion Analytics** (Order/DAU Conversion %)
- **User Engagement** (Navigation Sign-up %, Profile Sign-up %)

## 📈 Analysis Components

### 1. Month-on-Month Weekday Analysis
- Comprehensive breakdown of sales performance by weekday across months
- **Average Order Value (AOV)** trends by day of week
- **Net Sales** patterns and seasonal variations
- **Net Orders** distribution analysis

**Key Findings:**
- Saturdays show highest AOV performance (188.6 in November)
- Thursdays demonstrate strong consistency across months
- Significant growth trajectory from July to October

### 2. Predictive Forecasting Model
- **Linear regression model** for November sales prediction
- **R-squared value**: 0.061 (indicating moderate correlation with time)
- **Predicted November total sales**: ₹53,071,330
- Daily forecasted values for November 21-30, 2022

**Model Performance:**
- Multiple R: 0.247
- Standard Error: 599,854
- F-statistic: 9.155 (p-value: 0.003)

### 3. Sign-up Rate Analysis & Anomaly Detection
- **Statistical outlier identification** using Z-score methodology
- **Monthly averages**: July (20.2%), August (24.9%), September (15.2%), October (11.9%), November (17.3%)
- **Identified anomalies**: 6 significant outliers detected in August-September period

**Notable Outliers:**
- August 20: 35.5% (highest recorded)
- August 31: 37.82%
- September 2: 31.75%

### 4. Data Quality Assessment
- **Z-score analysis** across all metrics for anomaly detection
- **Correlation matrix** revealing key relationships between variables
- **Data cleaning recommendations** for identified inconsistencies

## 🔧 Technical Implementation

### Tools & Technologies
- **Microsoft Excel** with advanced formulas
- **Statistical Analysis** (Correlation, Regression, Z-score)
- **Data Visualization** (Charts, Pivot Tables)
- **Predictive Modeling** (Linear Regression)

### Data Processing Features
- Automated weekday categorization
- Month-over-month growth calculations
- Statistical outlier detection algorithms
- Correlation analysis between business metrics

## 📊 Key Business Insights

### Performance Trends
1. **Revenue Growth**: Steady increase from July (₹1.2M avg) to October (₹2.1M avg)
2. **User Acquisition**: Strong correlation between new installs and sales performance
3. **Conversion Optimization**: Sign-up rates show seasonal patterns requiring strategic intervention

### Operational Recommendations
1. **Weekend Strategy**: Capitalize on Saturday's high AOV performance
2. **Anomaly Investigation**: Review August outliers for replicable success factors
3. **Forecasting Accuracy**: Implement additional variables for improved prediction models

## 📋 Data Structure

The dataset contains 143 daily records with 12 key performance indicators:
- Date range: July 1 - November 20, 2022
- Complete daily metrics without missing values
- Comprehensive business intelligence coverage

## 🚀 Future Enhancements

- **Advanced ML Models**: Implement time series forecasting (ARIMA, Prophet)
- **Real-time Dashboard**: Connect to live data sources
- **Segmentation Analysis**: Customer cohort and behavioral analysis
- **A/B Testing Framework**: Statistical significance testing for business experiments

## 📁 File Structure

```
GIVA_Business_Analytics/
├── Data/ # Raw business metrics
├── Analysis/ # Statistical analysis sheets
├── Forecasting/ # Predictive models
├── Visualizations/ # Charts and graphs
└── Insights/ # Business recommendations
```

## 🤝 Contributing

This analysis framework can be extended for:
- Additional business metrics
- Advanced statistical modeling
- Real-time monitoring systems
- Cross-platform analytics integration

---

**Note**: This analysis is based on historical data from July-November 2022 and should be updated with current metrics for ongoing business intelligence applications.
