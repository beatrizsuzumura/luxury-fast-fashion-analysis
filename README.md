# 📊 Comparative Market Analysis: Fast Fashion vs. Luxury Sector

## 🎯 Project Objective
This project performs an automated quantitative analysis to compare **price resilience**, **volatility**, and **financial efficiency** between mass-market leaders (**Inditex/Zara**, **H&M**) and the luxury sector benchmark (**LVMH**).

It demonstrates the practical application of **Python** in automating **Equity Research**, **Strategic Controlling**, and **Market Intelligence** workflows.

## 🧠 Financial Methodology
Using 2-year adjusted historical data, the algorithm executes the following:

1.  **Base 100 Normalization:** Eliminates currency distortions between the Euro (EUR) and Swedish Krona (SEK) to allow for a "apples-to-apples" performance comparison.
2.  **Risk Assessment (Annualized Volatility):** Calculates the standard deviation of daily returns (`std * sqrt(252)`).
3.  **Fail-Safe Contingency System:** Implements a Monte Carlo simulation algorithm to ensure data pipeline integrity in case of external API downtime or rate limits.

## 🛠 Tech Stack
* **Python 3.x**
* **yfinance:** Real-time market data extraction via API.
* **Pandas & NumPy:** Time series manipulation and statistical modeling.
* **Matplotlib:** Data visualization for management reporting.

## 📈 Key Findings
> *The chart below illustrates the decoupling of LVMH's (Luxury) performance regarding traditional Retail players, highlighting the correlation between brand power and margin resilience.*

![Market Analysis Chart](market_chart.png)

## 👩‍💻 Author
**Beatriz**
* *B.Sc. in Business Economics & Controllership (USP - University of São Paulo)*
* *Master's in Accounting, Auditing & Performance Management (GEM - Grenoble École de Management, France)*
* *Focus: Corporate Finance, M&A, and Data Analytics.*

---
*This project is part of my professional portfolio bridging Corporate Finance and Technology.*
