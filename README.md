# E-Commerce Sales Performance Dashboard

The objective of this task was to design a stakeholder-ready dashboard featuring key performance indicators (KPIs), time-series trends, categorical breakdowns, and interactivity[cite: 1]. 

### **Key Features Built:**
* **Executive Summary Cards:** Instant visibility into core metrics (*Total Revenue, Total Orders, Total Customers, and Average Order Value*).
* **Time-Series Trend Analysis:** Tracks monthly and yearly revenue fluctuations to spot seasonal buying patterns.
* **Hierarchical Treemap Visualization:** Showcases revenue distribution across product Categories and individual Brands.
* **Demographic & Behavioral Analysis:** Evaluates spending habits across various customer age groups.
* **Interactive Filtering:** Global slicers for **Payment Mode**, **Category**, and **State** to allow stakeholders to dynamically drill down into specific data subsets[cite: 1].

**Relationships Established:**
* sales[Customer_ID] -> customers[Customer_ID] (Many-to-One)
* sales[Product_ID] -> products[Product_ID] (Many-to-One)

## 📋 Key Business Insights Uncovered
* **Top Revenue Drivers:** The **Electronics** category dominates overall sales volume, led heavily by top-performing brands like HP, Noise, and boAt.
* **Age Group Preferences:** The **26–35 age demographic** represents the highest revenue-generating segment, followed closely by younger buyers (18–25).
* **Sales Volatility:** Time-series tracking highlights distinct seasonal sales dips and spikes, providing actionable data for future inventory and marketing campaign planning.
