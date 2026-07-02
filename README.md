\# 📊 Amazon Sales Data Analytics \& Interactive Executive Dashboard



\## 📌 Project Overview

This repository contains a comprehensive end-to-end data analytics project evaluating transaction-level sales logs from the Amazon platform. Utilizing an empirical analysis of \*\*100,000 distinct orders\*\*, the business generated a total top-line revenue of \*\*$28,954,583.56\*\* with an Average Order Value (AOV) of \*\*$289.55\*\* per transaction. 



This project demonstrates proficiency in \*\*Data Engineering \& Automation (Python)\*\* alongside \*\*Business Intelligence Reporting (Microsoft Excel)\*\*. 



> \*\*⚠️ Data Architecture Constraints:\*\* The primary source dataset lacks a native `Profit` tracking column. Operational efficiency and risk of margin loss are tracked using systemic proxy variables, including transactional volume density, item category weights, and shipping-to-unit cost configurations.



\---



\## 🛠️ Repository Architecture

```text

├── data/

│   └── Amazon\_Sales.csv                  # Immutable raw source transaction log

├── notebooks/

│   └── amazon\_sales\_analysis.ipynb       # Python data cleaning and initial data visualization

├── output/

│   └── Amazon\_Sales\_Dashboard\_Final.xlsx # The generated interactive Excel file

└── README.md                             # Repository landing page and project report

