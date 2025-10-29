📖 Overview
This repository contains a comprehensive data science analysis of 44,629 coffee transactions from the Ethiopian Commodity Exchange (ECX), covering January 2018 to March 2021. The project uncovers key market dynamics in Ethiopia's coffee trade—one of the world's leading coffee producers, where coffee accounts for 30–35% of export revenues and supports over 15 million livelihoods.
Using Python-based tools, the analysis reveals insights like a strong negative price-volume correlation (r = -0.88, indicating bulk discounts), a 44% premium for Harar coffee (2,036.15 ETB/quintal), seasonal peaks in February (1,501.08 ETB/quintal), and a Prophet forecast predicting a surge to 2,194 ETB/quintal by June 2021. It addresses data quality challenges (e.g., 40% "Unknown" grades) and provides recommendations for producers, exporters, and policymakers.
Developed as part of an INSA internship by Besufekad Ayalkbet (Data Science, Debre Birhan University). Contact: besufekadbabibaw@gmail.com.
🚀 Features

Exploratory Data Analysis (EDA): Statistical summaries, correlations, and trends using pandas and scipy.
Visualizations: Interactive plots for pricing by origin, monthly seasonality, and warehouse volumes.
Forecasting: Time-series predictions with fbprophet (5.2% error rate).
Reporting: Professional LaTeX document with tables, figures, and stakeholder recommendations.
Key Insights:

Harar premium: 44% above average.
Gimbi logistics hub: 1.92M kg handled.
Grade volatility from 40% "Unknown" classifications.



🛠️ Tech Stack

Language: Python 3.8+
Core Libraries:

Data Processing: pandas, numpy
Statistics: scipy
Visualization: matplotlib, seaborn
Forecasting: fbprophet


Environment: Google Colab (Jupyter notebooks)
Reporting: LaTeX (sn-jnl template)
Other: Git for version control
