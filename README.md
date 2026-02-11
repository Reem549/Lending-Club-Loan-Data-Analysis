# Lending-Club-Loan-Data-Analysis
Developed an end-to-end loan risk analysis project using the Lending Club dataset to identify key factors influencing loan default. Built interactive dashboards and predictive insights to support data-driven credit risk assessment and improve lending decision-making.
## Business Challenge
- Portfolio: 1,000 loans totaling $15M
- Current Status: 54.5% fully paid, 32.1% current, 13% defaulted
- Core Challenge: Identify where credit risk is concentrated and how to manage it without sacrificing profitability

---

## Key Insights
1. **Loan Term:**  
   - 60-month loans account for 64% of defaults, while 36-month loans have fewer defaults.
2. **Debt-to-Income (DTI):**  
   - Borrowers with DTI 30–40% have the highest default rate (32.83%)
   - DTI <10% shows the lowest risk
3. **Income & Employment Stability:**  
   - Lower- and mid-income segments are riskier
   - Unknown employment tenure increases default probability
4. **Financial Behavior:**  
   - Borrowers with outstanding balances of 25K–50K show the highest default
   - Longer hardship duration strongly correlates with default
5. **Profitability:**  
   - Higher interest rates do not always translate to higher returns
   - Grade B loans deliver the strongest net return; Grade E performs poorly due to defaults

---

## Strategic Recommendations
1. Apply stricter approval criteria for 60-month loans
2. Implement stronger DTI-based risk controls
3. Prioritize early intervention for hardship cases
4. Improve data quality in employment and utilization fields
5. Rebalance portfolio toward segments with stronger risk-adjusted returns (e.g., Grade B)

## Tools & Technologies
- **Python**: Data cleaning, analysis, visualization
- **MSSQL**: Data querying and aggregation
- **Power BI**: Interactive dashboards and visualization


