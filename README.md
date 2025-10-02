# 📊 Portfolio Optimization with Riskfolio

This project demonstrates portfolio optimization using the [Riskfolio-Lib](https://riskfolio-lib.readthedocs.io/) library in Python.  
It applies **Modern Portfolio Theory (MPT)** to construct an efficient portfolio of global equities, using historical return and risk data.

---

## 🚀 Project Overview
- Collects daily stock prices via **Yahoo Finance (`yfinance`)**  
- Computes **returns and covariance matrix** (Ledoit-Wolf shrinkage)  
- Runs optimization under **Markowitz Mean-Variance (MV)** model  
- Applies **industry constraints** (e.g. Technology ≤ 60%, Healthcare ≤ 20%, Financials ≤ 20%)  
- Visualizes portfolio allocations with pie charts and bar plots  

---

## 📂 Files
- `portfolio_optimizer.ipynb` → Main Google Colab notebook  
- `portfolio_optimizer.py` → Python script version  
- `plots/` → Visualization outputs (allocation charts, covariance heatmaps)

---
