# Mutual Fund Performance Analysis (Exploratory)

## Project Overview
This project is an exploratory data analysis of Indian mutual fund schemes using publicly available data.  
The objective was to understand how returns, volatility, expense ratios, and fund maturity interact, and to build a simple, transparent framework to compare funds on a risk–return basis.

The focus of this project is on structured analysis, clear assumptions, and interpretability rather than complex optimization or predictive modeling.

---

## Objectives
- Explore risk–return characteristics across a large set of mutual funds  
- Compare funds using interpretable financial metrics  
- Build a rule-based scoring framework to rank funds under different assumptions  
- Present insights in a clear and decision-friendly format  

This project was developed as a learning and research exercise and is not intended as a production or trading system.

---

## Dataset
- Approximately 2,500 mutual fund schemes  
- Publicly available historical performance and fund-level data  
- Variables include returns over different horizons, expense ratios, fund category, and basic risk indicators  

---

## Methodology

### 1. Data Exploration
- Examined distributions of returns, expenses, and fund categories  
- Identified missing values and inconsistencies  
- Performed basic descriptive and correlation analysis  

### 2. Data Cleaning
- Handled missing values and outliers using simple, explainable rules  
- Standardized numeric metrics to enable fair comparison  
- Ensured consistency across fund categories  

### 3. Feature Construction
- Used existing performance metrics such as returns and expense ratios  
- Derived simple comparative measures like volatility-adjusted returns  
- Prioritized interpretability over complexity  

### 4. Scoring Framework (Rule-Based)
Funds were compared using a weighted scoring approach based on intuitive financial considerations:
- Longer-term performance (returns)  
- Cost efficiency (expense ratio)  
- Consistency of positive performance  
- Fund maturity / experience  

Weights were chosen heuristically to reflect risk–return trade-offs.  
Results were reviewed under different weight assumptions to understand sensitivity.

> This framework is intended for comparative analysis and learning, not for prediction or live deployment.

---

## Tools and Technologies
- **Python:** Pandas for data manipulation and analysis  
- **Scikit-learn:** Basic preprocessing (scaling)  
- **Excel:** Validation and supplementary analysis  
- **Power BI:** Interactive dashboard and visualization  

---

## Key Observations
- Expense ratios vary significantly across fund categories and impact long-term outcomes  
- Certain funds deliver comparable returns with lower volatility and costs  
- Simple, transparent rules can effectively narrow a large investment universe for further analysis  

These observations are illustrative and based on historical data.

---

## Dashboard
An interactive Power BI dashboard was created to:
- Filter funds by category, risk level, and performance  
- Compare key metrics such as returns and expense ratios  
- Summarize insights visually for easier interpretation  

The dashboard is intended for exploration and learning rather than automated decision-making.

---

## Limitations
- Analysis is based solely on historical, publicly available data  
- Transaction costs, taxes, and real-time constraints are not considered  
- No predictive modeling or live performance testing  
- Results depend on chosen assumptions and weights  

---

## Conclusion
This project demonstrates how structured data analysis and simple quantitative reasoning can support financial evaluation in a transparent and interpretable manner.

The focus was on:
- Data cleaning and exploration  
- Clear assumptions  
- Practical risk–return thinking  
- Effective communication of insights  

This work reflects my interest in quantitative analysis, financial research, and decision-oriented analytics, and serves as a foundation for deeper learning.

---

## Disclaimer
This project is for educational and analytical purposes only and does not constitute investment advice.
