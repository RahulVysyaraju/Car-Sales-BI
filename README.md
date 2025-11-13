<p align="center">
  <img src="logo_global_auto.png" alt="Global Auto Insights Logo" width="300" height="100">
</p>

# 🚗 Global Auto Sales Analytics Dashboard (Power BI)

Interactive Power BI dashboard analyzing global car sales performance, revenue trends, and geographical distribution for Global Auto Insights.

## ✨ Project Objective & Overview

This project features a comprehensive and interactive business intelligence dashboard created in **Power BI** to provide key stakeholders with a clear, 360-degree view of global car sales performance. The analysis is built across four key pages: *Executive Dashboard*, *Map*, *Products*, and *Dealers*.

## 🛠️ Technology Stack & Files

| Component | Tool / Language | Purpose in Project |
| :--- | :--- | :--- |
| **Dashboard** | **Power BI Desktop** | Visualization and reporting solution. |
| **Data Modeling** | **DAX** (Data Analysis Expressions) | Created complex time-intelligence measures (YOY Growth, Monthly Revenue, etc.). |
| **ETL & Cleaning** | **Power Query (M Language)** | Data transformation, cleaning, and building the dimensional model from the source. |
| **Source Data** | **Excel (`.xlsx`)** | Primary source file containing sales transactional data. |

### Repository Files:

| File Name | Description |
| :--- | :--- |
| `[Your Project Name].pbix` | The fully functional Power BI report file. |
| `[Your Excel File Name].xlsx` | The source data file used for the analysis. |
| `README.md` | This file—project overview and documentation. |
| `Data_Source_Details.txt` | Detailed log of the data source and collection method. |
| `images/` folder | Contains the **`logo_global_auto.png`** and all report screenshots. |

---

## 📊 Key Features and Insights Delivered

### 1. Executive Dashboard (Summary)
* **KPI Tracking:** Displays critical metrics like **$241.6M Total Revenue**, **3,750 Total Units Sold**, and **$130.2K Average Revenue** per deal.
* **Performance Variance:** Features a gauge showing **$6.9M Monthly Revenue** with percentage change comparison to the previous month.
* **Strategic Insights:** Ranks the **Top 5 Countries by Revenue** (e.g., Indonesia) and the **Top 5 Car Brands**, identifying **Toyota** as the best-seller brand.

### 2. Dealer & Geographical Analysis
* **Global Mapping** : Analyzes **Total Revenue by Countries**, allowing filtering by **Affordable, Expensive, and Medium** price segments for targeted market analysis.
* **Dealer Scatter Plot:** Correlates **Dealer Performance (Volume vs. Value)** to assess efficiency and scale across branches globally.
* **Segmentation:** Visualizes Total Deals broken down by Price Segment (e.g., Medium accounting for $\approx 64\%$ of total units sold).

### 3. Products and Trends
* **Best Seller Focus:** Details the performance of the **Best Seller Car (Toyota Avalon)** with trends and monthly metrics.
* **Time Series:** Includes clear line charts for historical **Revenue Trends** and **Monthly Units Sold Trends** from 2017 to 2020.

---

## 🚀 Getting Started (How to Use)

1.  **Download:** Clone or download the entire repository contents.
2.  **Software:** Open the **`[Your Project Name].pbix`** file in **Power BI Desktop**.
3.  **Data Connection:** Since the source Excel file is included, the report should automatically connect and load the data model, allowing full interactivity and exploration of the visualizations.

---

This is your final, comprehensive `README.md`! Remember to **create the `images/` folder** and place your logo file inside it before uploading.
