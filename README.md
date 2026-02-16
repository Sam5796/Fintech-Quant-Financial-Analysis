
# 📊 Comparative Financial Statement Analysis (Retail)

**Role Focus:** Financial Analyst | BI Developer | Data Strategist
**Tech Stack:** Fundamental Analysis, Ratio Modeling, GAAP Accounting (ASC 606)

## 1. The Business Strategy (The "Why")
**Objective:** To perform a fundamental analysis of two major retail competitors (Macy's vs. Kohl's) to determine financial health and investment viability.
* **Strategic Goal:** Translate unstructured 10-K data into actionable **KPIs** (Liquidity, Solvency, Profitability) to guide equity investment and credit risk decisions.

## 2. Methodology (The "How")
* **Data ETL:** Extracted and normalized financial data from 2021-2023 10-K Annual Reports.
* **Policy Audit:** Verified **Revenue Recognition** compliance with Accrual Accounting standards to ensure data integrity.
* **Ratio Modeling:**
    * **Liquidity:** Current Ratio analysis to test short-term solvency.
    * **Leverage:** Debt-to-Equity and Times Interest Earned (TIE) modeling.
    * **Profitability:** Return on Equity (ROE) decomposition.

## 3. Key Insights (The "View")
* **Profitability Collapse:** Identified a critical risk in Macy's performance, where ROE plummeted from **46% (2021)** to **2.5% (2023)**.
* **Leverage Risk:** Modeled the Debt-to-Equity trends, revealing that Kohl's increased its leverage from 2.2x to 2.6x, signaling higher financial risk in a rising interest rate environment.
* **Turnaround Signal:** Detected Kohl's recovery from a Net Loss in 2022 to positive Net Income in 2023, though margins remain tight.



# 🏦 LendingClub: Fintech Transformation & Credit Risk Analysis

**Role Focus:** Fintech Strategist | Credit Risk Analyst | Product Manager
**Tech Stack:** Python (Logistic Regression), Pandas, Strategic Analysis (SWOT)

## 1. The Business Strategy (The "Why")
**Objective:** Evaluate LendingClub’s strategic pivot from a P2P marketplace to a "Marketplace Bank" (post-Radius Bank acquisition) and validate the accuracy of their algorithmic underwriting.
* **Strategic Insight:** The acquisition allowed LendingClub to replace high-cost warehouse credit with low-cost consumer deposits, significantly improving Net Interest Margin (NIM).

## 2. Technical Methodology (The "How")
* **Credit Risk Modeling:** Built a **Logistic Regression** model to calculate the **Probability of Default (PD)** based on FICO, DTI, and Income Verification.
* **Pricing Validation:** Performed correlation analysis between *Predicted PD* and *Actual Interest Rates* to verify that the algorithm correctly prices risk (Risk-Based Pricing).
* **Performance Metric:** Optimized for **ROC-AUC** to balance the cost of False Negatives (Defaults) vs. False Positives (Lost Interest Income).

## 3. Key Findings (The "View")
* **Segment Profitability:** Identified that **Renters** offer higher yields (13.5%) but significantly higher default risks (23.6%) compared to **Homeowners** (12.8% yield / 17% default).
* **Model Validation:** The model confirmed that FICO score and DTI are the strongest predictors of default, validating the bank's core scorecard variables.
* **Strategic Recommendation:** Recommended expanding into **Auto Refinancing** to utilize the new low-cost deposit base for secured, lower-risk lending.

---

# 📉 Hedge Fund Strategy: Cross-Industry Financial Analysis

**Role Focus:** Quant Researcher | Equity Analyst | Portfolio Management
**Tech Stack:** Python, Pandas, Seaborn, Fundamental Analysis

## 1. The Business Strategy (The "Why")
**Objective:** Assist a Hedge Fund Manager in allocating capital by benchmarking the financial health of companies across **Technology**, **FMCG**, and **Real Estate** sectors.
* **Strategic Goal:** Normalize financial data to identify sector-specific risk profiles. Specifically, to determine if the high debt load in Real Estate is a risk factor or a growth driver.

## 2. Technical Methodology (The "How")
* **Data Engineering:** Merged disparate Balance Sheet and Income Statement datasets to calculate unified financial ratios.
* **Ratio Modeling:**
    * **Leverage (Debt-to-Equity):** Quantified financial distress risk.
    * **Profitability (Gross Margin):** Quantified operational efficiency.
* **Hypothesis Testing:** Used **Seaborn Regression Plots** to analyze the correlation between leverage and profitability within specific sectors.

## 3. Key Findings (The "View")
* **Sector Benchmarking:**
    * **Real Estate** carries the highest risk (Leverage Ratio: **5.69**), nearly 3x higher than the Tech sector (1.77).
    * **FMCG** operates on the thinnest margins (Profitability: **0.51**), relying on volume rather than pricing power.
* **Investment Insight:** The analysis confirmed a **Positive Correlation** between leverage and profitability in Real Estate.
    * *Actionable Takeaway:* In the current dataset, Real Estate companies utilizing more debt are effectively generating superior returns, validating a "High Leverage" strategy for this specific asset class.


