# 🛒 Walmart Supply Chain Optimization Strategy
Strategic analysis of Walmart's supply chain identifying a 1.69x hidden demand peak and optimizing inventory for 27 priority stores using Python

![Banner Image](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge) ![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge)

## 📌 Executive Summary
**Objective:** Optimize Q4 inventory allocation to minimize stockouts during high-demand periods.
**Impact:** Identified a **1.69x hidden demand surge** (Pre-Christmas Rush) often missed by standard forecasting, recommending a targeted stock multiplier for **27 priority stores**.

---

## 👥 Target Stakeholders
This project is designed to assist:
1. 🚛 Supply Chain Managers: To optimize safety stock levels during non-holiday peaks.
2. 🏢 Operations Directors: To prioritize resource allocation for high-impact stores (Pareto efficiency).
3. 🏷️ Category Managers: To align pricing strategies with actual consumer demand cycles.

## 💼 Business Problem
Retail supply chains often rely on static "Holiday" flags. Historical data (2010-2012) revealed that reliance on these flags leads to:
1.  **Stockouts:** In Weeks 50-51 (Non-holiday) when actual shopping peaks.
2.  **Overstock:** In Week 52 (Holiday) when demand naturally drops.

## 🔍 Key Insights (The "Aha!" Moments)
### 1. The "Hidden Peak" Phenomenon
- Analysis showed the true shopping peak occurs **14 days before Christmas**.
- **Action:** Shift inventory loads to Week 49-50, not Week 52.

### 2. Pareto Efficiency (80/60 Rule)
- **60% of stores (27 units)** generate **80% of total revenue**.
- **Action:** Prioritize logistics resources for these 27 core locations.

## 🛠️ Tech Stack
- **Data Manipulation:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn
- **Strategy:** Pareto Analysis, Time-Series Decomposition

## 🚀 How to Run
1. Clone the repo:
   ```bash
   git clone [https://github.com/ryanroshandy55/Walmart-Supply-Chain-Optimization.git](https://github.com/ryanroshandy55/Walmart-Supply-Chain-Optimization.git)

   ---
## ⚠️ Disclaimer
This is a personal portfolio project for educational purposes only.
The dataset used is public historical data (2010-2012) sourced from Kaggle.
This project is **not affiliated, associated, authorized, endorsed by, or in any way officially connected with Walmart Inc.**
