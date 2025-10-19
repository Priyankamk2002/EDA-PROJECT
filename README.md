# Nifty 500 Stock Market Analysis

## Project Overview
This project analyzes the **Nifty 500 stock market dataset**, scraped from [screener.in](https://www.screener.in/).  
The goal is to explore **key performance indicators (KPIs)** of companies, identify trends, and provide **data-driven insights**.

---

## Domain Knowledge
The stock market domain involves monitoring:

- Company metrics like **CMP, Market Cap, P/E Ratio, Dividend Yield**  
- Quarterly profits and sales trends  
- Return metrics like ROCE  
- Investor decision-making  

Effective analysis helps to:

- Identify high-performing companies  
- Compare KPIs across sectors  
- Detect unusual patterns in stock performance  

---

## Dataset Structure & Column Descriptions

| Column | Description |
|--------|-------------|
| Company Name | Name of the company |
| CMP Rs. | Current Market Price of the stock (in INR) |
| Price to Earnings Ratio | P/E ratio, indicating how much investors are willing to pay per rupee of earnings |
| Mar Cap Rs.Cr. | Market capitalization in crores |
| Div Yld % | Dividend yield percentage |
| NP Qtr Rs.Cr. | Net profit for the quarter in crores |
| Qtr Profit Var % | Quarterly profit variation percentage compared to previous quarter |
| Sales Qtr Rs.Cr. | Quarterly sales in crores |
| Qtr Sales Var % | Quarterly sales variation percentage compared to previous quarter |
| ROCE % | Return on Capital Employed percentage, showing efficiency in using capital |

**Notes:**  
- Data was scraped from **screener.in** using Python.  
- All 483 companies have complete data for these 10 columns.  

---

## Project Objectives

1. Perform **exploratory data analysis (EDA)** on scraped stock data  
2. Analyze KPIs like CMP, Market Cap, P/E Ratio, Dividend Yield, Quarterly Profit and Sales, ROCE  
3. Identify **top-performing companies**  
4. Explore relationships between financial metrics  
5. Provide actionable insights for investors  

---

## Tools & Techniques
- **Python:** Pandas, NumPy  
- **Visualization:** Matplotlib, Seaborn  
- **Analysis:** EDA, correlation analysis, trend detection  

---

## Conclusion
This project demonstrates how **scraped stock market data** can be analyzed to understand company performance and quarterly trends.  
By exploring KPIs across companies, we can:  

- Identify **top-performing companies**  
- Understand **market trends and KPI relationships**  
- Provide insights for **investment decisions**
