# Customer Churn Analysis Dashboard

An interactive Tableau dashboard analyzing customer churn patterns for a telecommunications company. This project identifies key drivers of customer attrition and provides actionable insights for retention strategy.

## 📊 Dashboard Overview

**Tool:** Tableau  
**Data Source:** Telecom customer dataset (6,524 customers)  
**Key Metric:** 27.4% churn rate (1,790 churned customers)

## 🎯 Business Problem

Understanding why customers leave is critical for reducing churn and improving lifetime value. This analysis examines:
- Which customer segments have the highest churn rates?
- What are the primary reasons customers cancel service?
- How do contract types and payment methods impact retention?
- Which demographics and usage patterns predict churn?

## 📈 Dashboard Components

### 1. Overview Dashboard
- **Churn metrics:** Overall rate, total customers, churned count
- **Geographic analysis:** Churn distribution by state with interactive map
- **Top churn reasons:** Competitor offers, pricing, support issues ranked by frequency
- **Segmentation:** Churn by contract type and category

### 2. Age Brackets and Groups
- **Age analysis:** Churn rate peaks at 35% for customers 65+ years old
- **Group accounts:** Solo customers churn at 20% vs. 5% for group plans
- **Interactive filters:** Drill down by contract type, data plan, and payment method

### 3. Payment Methods and Contract Types
- **Contract insight:** Month-to-month contracts show 46% churn vs. 11% for annual contracts
- **Payment analysis:** Direct debit users have highest retention
- **Service calls correlation:** 1,565 total service calls averaging 0.73 per customer

### 4. Data and International Plans
- **Data plan impact:** Unlimited plan users show 35% churn rate
- **International calling:** Customers without international plans churn at 71% when actively traveling
- **Revenue drivers:** Extra charges average $3.35 (data) and $32.58 (international)

## 💡 Key Insights

1. **Contract length matters:** Annual contracts reduce churn by 76% compared to month-to-month
2. **Competitor threat:** 45% of churn is driven by better competitor offers or pricing
3. **Senior vulnerability:** Customers 65+ have 2x the churn rate of younger segments
4. **Payment friction:** Paper check users churn at 50% vs. 30% for direct debit
5. **International travelers:** High churn (71%) among active international users without plans

## 🛠️ Technical Skills Demonstrated

- Data visualization and dashboard design in Tableau
- Interactive filtering and parameter controls
- Geographic mapping and spatial analysis
- Multi-dashboard storytelling with consistent design
- Business metrics calculation and KPI tracking
- Customer segmentation and cohort analysis

## 📁 Files

- `Churn_Analysis.twbx` - Tableau packaged workbook (interactive dashboards)
- `Churn_Analysis.pdf` - Static dashboard views for quick reference

## 🎯 Business Applications

This analysis framework can be applied to:
- Developing targeted retention campaigns for high-risk segments
- Optimizing contract offerings and pricing strategy
- Improving customer service based on churn drivers
- Forecasting revenue impact of retention initiatives

---

**View the interactive dashboards** by downloading the `.twbx` file and opening in Tableau Desktop or Tableau Reader (free).
