# ♻️ Waste Management Performance Dashboard

![Power BI](https://img.shields.io/badge/Tool-Power%20BI-yellow?logo=powerbi)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

# 📊 Smart Waste Management Performance Report

## 🔍 Overview
This project presents a **Smart Waste Management Dashboard** built using **Power BI** with **mock data generated in Python**. It simulates waste collection performance across various cities, helping stakeholders monitor key metrics like total waste, recycling rate, vendor efficiency, and carbon reduction.

The report assists in **data-driven decision-making** by visualizing trends, comparing vendor performance, identifying cost inefficiencies, and highlighting areas for sustainability improvements.

---

## 📈 Power BI Dashboard

You can view the live dashboard here:  
🔗 [Power BI Report - Smart Waste Management Dashboard](https://app.powerbi.com/view?r=eyJrIjoiNTRiNGZiNjYtZDg5Ni00ZGFlLWIxMGQtNjcxZDI1NTg0MjFkIiwidCI6ImViZTAyOTY0LTUwZWUtNGI3MS1iYjA3LWYyYjQ2YWZlN2QxMiJ9)

---

## 🖼️ Screenshots

**Main Dashboard:**  
![Smart Waste Dashboard Overview](./assets/screenshot_overview.png)

**Key Insights Page:**  
![Smart Waste Dashboard Insights](./assets/screenshot_insights.png)

---

## 🧪 Mock Data Generation (Python)

The dataset includes:
- Waste collection summary
- Cost optimization tracker
- Recycling performance
- Vendor scorecard
- Sustainability KPIs

Python was used to generate realistic mock data simulating weekly activity across four Canadian cities. The script creates five `.csv` files which are used in the Power BI dashboard.

### Sample Code Snippet:
```python
total_waste = round(np.random.uniform(1.0, 5.0), 2)
cost_per_ton = round(base_cost / waste, 2)
carbon = round(waste * np.random.uniform(0.7, 1.5), 2)

Mock data was generated using Python and Pandas, simulating:
- Waste collection data
- Cost optimization data
- Recycling performance
- Vendor metrics
- Sustainability indicators

> ✅ All mock datasets are stored in the `/data` folder as `.csv` files.

---

## ⚙️ Tech Stack

| Tool        | Purpose                        |
|-------------|--------------------------------|
| **Python**  | Data generation and preprocessing |
| **Pandas**  | DataFrames and mock data handling |
| **Power BI**| Dashboard creation and data visualization |

---

## 📁 Repository Structure

