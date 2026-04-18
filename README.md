# ACC102 Financial Analysis: AAPL, MSFT, TSLA (2021–2023)
---
## 1. Problem & User
This project analyzes the revenue trends and profit margins of three major technology companies (Apple, Microsoft, Tesla) from 2021 to 2023. The goal is to identify differences in their financial performance and connect these trends to their business models.

## 2. Data
- **Source**: Wharton Research Data Services (WRDS)
- **Access Date**: April 13, 2026
- **Key Fields**:
  - `conm`: Company name
  - `fyear`: Fiscal year
  - `revt`: Total revenue
  - `ni`: Net income

## 3. Methods
1.  Data extraction from WRDS with selected key variables
2.  Data cleaning in Python: removed missing values and converted data types
3.  Calculated profit margin (`net income / revenue`) for each company
4.  Created a line chart in Matplotlib to visualize revenue trends

## 4. Key Findings
- Microsoft shows steady revenue growth with the highest profit margin (over 30%)
- Apple maintains consistent and strong revenue performance
- Tesla has the fastest revenue growth but lower profit margins (10–15%)
- These differences reflect each company’s unique business model and industry characteristics

## 5. How to run
1.  Download all files in this repository
2.  Open `ACC102_Financial_Analysis.ipynb` in Jupyter Notebook
3.  Run all cells to reproduce the analysis and chart

## 6. Product link / Demo
This repository contains the complete code, raw data, and final chart for the analysis.

## 7. Limitations & next steps
- Limitation: The analysis is limited to three years of data and does not include external market factors
- Next steps: Add more years of data and compare performance against industry averages
