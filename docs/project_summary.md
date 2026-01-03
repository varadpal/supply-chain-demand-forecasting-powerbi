# Project Summary – AI-Driven Demand Forecasting & Inventory Optimization

## 📌 Project Context
This project focuses on analyzing and optimizing a company’s supply chain using data-driven methods. The goal was to improve demand forecasting accuracy, optimize inventory levels, and support operational decision-making using interactive Power BI dashboards.

The analysis uses daily SKU-level data covering demand, forecasting outputs, inventory movements, supplier performance, and logistics-related factors.

---

## 🎯 Business Problem
Supply chain operations often struggle with:
- Inaccurate demand forecasts
- Overstocking and stockouts
- Inefficient reorder policies
- High holding and distribution costs

This project addresses these challenges by combining **forecasting techniques** with **inventory optimization metrics** to improve service levels while controlling costs.

---

## 📊 Analytical Approach
The project was structured into four key analytical layers:

### 1. Demand Forecasting
- Compared multiple forecasting methods:
  - Moving Average
  - Exponential Smoothing
  - Prophet
  - XGBoost
- Evaluated forecast accuracy using:
  - Forecast Error
  - Absolute Error
  - MAPE (%)

### 2. Inventory Optimization
- Calculated:
  - Safety Stock
  - Reorder Point
  - Economic Order Quantity (EOQ)
- Monitored:
  - Opening vs Closing Inventory
  - Stockout and Backorder flags
  - Fill Rate (%)

### 3. Supply Chain Performance
- Analyzed supplier performance using:
  - On-time delivery rate
  - Lead time mean and variability
  - Transportation delays
- Identified high-cost suppliers and routes

### 4. Cost & Efficiency Analysis
- Evaluated:
  - Inventory holding costs
  - Order and distribution costs
  - Overstock percentage
- Compared inventory efficiency across regions

---

## 📈 Key Insights
- Forecast accuracy varies significantly by model and SKU, highlighting the importance of model selection.
- Regions with stable lead times show better inventory efficiency.
- A small number of suppliers contribute disproportionately to total supply chain cost.
- Optimized reorder points help maintain high fill rates while reducing excess inventory.

---

## 🛠 Tools & Technologies
- **Power BI**: Dashboarding, data modeling, DAX
- **Excel**: Data preprocessing and validation
- **Python (external)**: Forecast model generation
- **Analytics Techniques**:
  - Time series forecasting
  - Inventory management models
  - KPI-based performance tracking

---

## 📦 Dataset Overview
- Type: Simulated supply chain dataset (educational)
- Granularity: Daily, SKU-level
- Time period: Jan 2024 – Apr 2024
- Key dimensions:
  - SKU, Category, Region, Supplier, Warehouse
- Key metrics:
  - Demand, Forecast, Inventory, Cost, Lead Time

---

## 🎯 Project Outcome
This project demonstrates the ability to:
- Translate complex supply chain data into actionable insights
- Design decision-focused BI dashboards
- Apply forecasting and inventory theory to real-world scenarios
- Communicate insights clearly for business stakeholders

---

## 🔍 Future Enhancements
- Automate forecast model retraining
- Add scenario analysis for demand spikes
- Integrate service-level optimization constraints
- Deploy dashboard with live data connections
