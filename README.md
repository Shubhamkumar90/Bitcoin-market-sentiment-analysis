# Bitcoin Market Sentiment and Trader Performance Analysis

## Overview
This project explores the relationship between **Bitcoin market sentiment** and **trader performance (PnL)** using data from the **Hyperliquid trading platform** and the **Fear–Greed Index**.  
The goal is to understand how market psychology influences trading activity, risk behavior, and profitability.

---

## Objectives
- Examine how **trading behavior** changes across different sentiment phases (Fear → Greed).  
- Quantify the relationship between **market sentiment** and **trader performance** using **correlation analysis**.  
- Identify whether sentiment can serve as a **predictor of trader success** or if **discipline and strategy** dominate.  

---



## Key Findings

- **Trader activity and trade size** increase during *Greed* and *Extreme Greed* periods, showing stronger participation and confidence.  
- **PnL volatility** is highest in *Extreme Greed* phases, indicating greater risk-taking behavior.  
- **Correlation results:**  
  - Pearson correlation = **-0.083** (p = 0.071)  
  - Spearman correlation = **0.040** (p = 0.384)  
- Both tests show **no statistically significant relationship** ($p > 0.05$).  
- Therefore, the **null hypothesis ($H_0: \rho = 0$)** is **not rejected** — daily sentiment does not directly predict trader profitability.  
- A small subset of traders **consistently outperform regardless of sentiment**, highlighting the value of **strategy and discipline** over emotional bias.  

---

## Methods
1. **Data Sources**
   - Bitcoin market sentiment from the **Fear–Greed Index**
   - Trader performance data from **Hyperliquid**

2. **Analytical Techniques**
   - Descriptive analysis of trader behavior
   - Pearson and Spearman correlation tests
   - Visualization of sentiment trends and PnL distributions

3. **Hypothesis Testing**
   - $H_0$: No significant linear relationship between sentiment and trader performance ($\rho = 0$)  
   - $H_1$: Significant relationship exists ($\rho \neq 0$)  

---

## Conclusion

This analysis explored the relationship between **Bitcoin market sentiment** and **trader performance** using **Hyperliquid trading data** and the **Fear–Greed Index**.

### Key Findings

- **Trader activity and trade size** increase during *Fear* and *Greed* periods, reflecting stronger market participation and confidence.  
- **PnL volatility** is highest in *Extreme Greed* phases, suggesting increased **risk-taking behavior** during bullish sentiment.  
- **Correlation tests (Pearson and Spearman)** indicate **no statistically significant relationship** between sentiment and trader performance ($p > 0.05$).  
- The **null hypothesis** ($H_0: \rho = 0$) is therefore **not rejected**, implying that **daily sentiment does not directly predict trader profitability**.  
- A **small group of traders consistently outperform** regardless of sentiment, emphasizing the value of **strategy and discipline** over emotional bias.  

