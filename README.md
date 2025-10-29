# Ethiopian Coffee Trade Analysis

[![GitHub stars](https://img.shields.io/github/stars/bawcode/ethiopian-coffee-trade-analysis)](https://github.com/bawcode/ethiopian-coffee-trade-analysis/stargazers)
[![License](https://img.shields.io/github/license/bawcode/ethiopian-coffee-trade-analysis)](https://github.com/bawcode/ethiopian-coffee-trade-analysis/blob/main/LICENSE)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)

## Overview
This repository contains a comprehensive data science analysis of **44,629 coffee transactions** from the **Ethiopian Commodity Exchange (ECX)**, spanning **January 2018 to March 2021**. The project uncovers critical market dynamics in Ethiopia's coffee trade — the birthplace of coffee — where it accounts for **30–35% of export revenues** and supports **over 15 million livelihoods**.

Using Python tools, the analysis reveals:
- Strong **negative price-volume correlation** (`r = -0.88`) → bulk discounts
- **44% premium** for **Harar coffee** at **2,036.15 ETB/quintal**
- **Seasonal peak in February** at **1,501.08 ETB/quintal**
- **Gimbi** as top logistics hub handling **1.92M kg**
- **Prophet forecast**: Price surge to **2,194 ETB/quintal by June 2021**
- Data challenge: **40% "Unknown" grades** causing volatility

Developed during an **INSA internship** by **Besufekad Ayalkbet** (Data Science, Debre Birhan University).  
Contact: [besufekadbabibaw@gmail.com](mailto:besufekadbabibaw@gmail.com)

---

## Features
- **Exploratory Data Analysis (EDA)** with `pandas` & `scipy`
- **Interactive visualizations** (monthly trends, origin pricing, warehouse volumes)
- **Time-series forecasting** using `fbprophet` (5.2% error)
- **Professional LaTeX report** with tables, figures, and citations
- Actionable **recommendations** for producers, exporters, and policymakers

---

## Tech Stack
- **Language**: Python 3.8+
- **Libraries**:
  - `pandas`, `numpy` – data processing
  - `scipy` – statistical analysis
  - `matplotlib`, `seaborn` – visualization
  - `fbprophet` – forecasting
- **Environment**: Google Colab (Jupyter notebooks)
- **Reporting**: LaTeX (`sn-jnl` template)
- **Version Control**: Git & GitHub

---

## Repository Structure
