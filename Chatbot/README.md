# Financial Chatbot — Documentation

## Overview
This chatbot dynamically answers financial questions about Apple, Microsoft, and Tesla by performing real-time calculations on historical financial data loaded from a CSV file (`company_financials.csv`). It leverages the pandas library to handle data filtering, calculations, and summaries.

## Supported Queries and Calculations

| Query                                          | Explanation                                                     |
|------------------------------------------------|-----------------------------------------------------------------|
| What is the total revenue for [Company]?       | Retrieves the company’s total revenue for the latest fiscal year. |
| How has net income changed for [Company]?      | Calculates the percentage change in net income between the last two years. |
| What is the asset to liability ratio for [Company]? | Computes the ratio of total assets to total liabilities for the latest year. |
| What is the operating cash flow for [Company]? | Fetches the latest year’s cash flow from operating activities. |
| Which company has the highest asset to liability ratio? | Compares all companies' latest asset/liability ratios and returns the highest. |

## Usage Instructions

1. Ensure you have Python 3.x and pandas installed (`pip install pandas`).
2. Place `chatbot_financials.py` and `company_financials.csv` in the same directory.
3. Run the chatbot script:
