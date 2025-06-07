# 🧠 Sales Performance and Customer Engagement Pipeline

A scalable, end-to-end data pipeline designed to automate sales incentive computation and derive actionable insights from customer spending behavior — built using Python, Pandas, MySQL, and Jupyter.

---

## 🚀 Project Overview

This project automates monthly sales incentive calculations for top-performing sales personnel across retail stores and builds a customer data mart to analyze spending patterns for personalized promotions and loyalty programs.

Key goals:
- Automate incentive logic for sales teams across stores
- Track and rank top performers monthly
- Analyze customer purchase behavior to support targeted marketing
- Deliver clean, analytics-ready data marts

---

## 🏗️ Tech Stack

- **Python (Pandas, NumPy)** – Data manipulation and processing
- **MySQL** – Dimension table storage (customer, store, sales team)
- **Jupyter Notebook** – Development environment
- **SQLAlchemy** – Database connection and querying
- **PySpark (for initial prototype)** – Large-scale simulation (optional)

---

## 📊 Data Marts

1. **Customer Data Mart**  
   Contains enriched customer profiles with purchase behavior, enabling marketing insights.

2. **Sales Team Data Mart**  
   Tracks monthly sales performance, computes incentives (1% for top performer per store), and supports real-time eligibility checks.

---

## 🔁 Workflow Summary

1. Generate sample sales data (Python script)
2. Connect to MySQL to fetch dimension tables
3. Perform multi-stage joins and transformations
4. Apply window functions to rank and calculate incentives
5. Build and export final data marts

---

## ✅ Features

- 🔁 Fully automated incentive logic
- ⚡ Fast and optimized with Pandas window functions
- 📦 Reusable, modular Jupyter notebook pipeline
- 📈 Real-time insights into sales performance & customer spend

---


