# 📈 E-Commerce Capital Allocation & Statistical Diagnosis
**A Strategic Audit of a $32.87M Portfolio using Python (Pandas, Statsmodels, Seaborn)**

## 🎯 Executive Overview
This repository contains a comprehensive statistical audit of an e-commerce dataset comprising **50,000 orders**. The project’s primary objective was to move beyond descriptive analytics to identify actionable "Alpha"—specifically, a **$4.59M revenue recovery opportunity** currently lost to an ineffective discount program.

### [📥 Download the Full Technical Report (PDF)](./Statistical_Diagnosis_Capital_Allocation.pdf)

---

## 🚀 Key Insights & Findings
* **Price Inelasticity:** Modeling $\log(\text{Quantity})$ vs $\log(\text{Price})$ revealed an $R^2$ of effectively zero (**0.00002**). Customers are not responsive to discounts, meaning the current **$4.59M** in total discount spend is a direct margin leak with no volume benefit.
* **Regional Alpha:** Identified the **Middle East** as a "Tier 1" segment with an **8.3% AOV premium** ($663.88 vs $657 global avg), justifying a directional shift in marketing spend.
* **Structural Symmetry:** Nested F-tests and ANOVA confirmed that the portfolio is remarkably stable across categories and regions, allowing for a centralized capital allocation framework.
* **Payment Rail Optimization:** Moving the high-volume North American cohort toward **Wallet/UPI** payments is modeled to save approximately **$43,607** in transaction overhead.

---

## 🔍 Methodology
The analysis was conducted in Python using a multi-layered diagnostic approach:

1.  **OLS Regression:** Mapped the primary revenue architecture ($R^2 = 0.882$).
2.  **ANOVA & Post-hoc Testing:** Used to identify variance across product categories and geographies ($p = 0.918$).
3.  **Log-Log Modeling:** Calculated precise Price Elasticity of Demand to confirm unit-inelasticity.
4.  **Nested F-Testing:** Validated structural consistency and ruled out complex interaction effects ($p = 0.320$).
5.  **Volatility Analysis:** Calculated Coefficient of Variation (CV) to identify "Volatility Arbitrage" opportunities in peak variance months (July/October).

---

## 📊 Visualizations


> **The "Flatline" Evidence:** This plot demonstrates the near-zero correlation between discount percentages and quantity sold, providing the mathematical mandate to eliminate the discount program.


> **Regional Distribution:** Visualizing the Middle East’s AOV premium over other global regions.


> **Payment Heatmap:** Pinpointing the North America/Wallet and Middle East/CoD intersections as the primary liquidity nodes.

---

## 🛠️ Repository Structure
* `Statistical_Diagnosis_Capital_Allocation.pdf`: The formal executive report.
* `amazon_sales_dataset.csv`: The core dataset ($n=50,000$).
* `capital_allocation_memo_final.pdf`: The original summary memo.

---

## 💡 Strategic Recommendations
1.  **Rollback Discounts:** Eliminate all discount tiers over a 30-day period to recapture **$4.59M**.
2.  **Segmented Acquisition:** Over-index marketing spend on the **Middle East + Wallet** cohort.
3.  **Automate Reviews:** Since 73% of revenue comes from products rated <4.0, shift manual review-gen spend to automated post-purchase workflows.
