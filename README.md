# Credit Analysis Case Study: (KES 5 Billion Loan)

Illustrative case study based on public annual reports. Not a real credit decision. This is a learning project. "Hypothetical Lender" is a made-up institution. I am not affiliated with NCBA Group PLC and nothing here is investment, credit or legal advice.

# Table of contents

- What is this project?
- Why credit analysis matters
- Plain-English glossary
- The proposed loan
- Sheet-by-sheet guide
- How the analysis works, step by step
- Key findings
- Stress tests and sensitivity tables
- Two kinds of "interest coverage"
- Assumptions
- How I cleaned up and checked the model
- Known limitations
- How to use the file
- Ideas for extending the project
- Skills demonstrated
- Disclaimer

1. What is this project?

When a company asks a bank for a large loan, the bank's credit team writes a credit memo. It is a structured document that answers one question:

"If we lend this money, will we get it back and are we paid enough for the risk?"

This project is a complete credit memo for an imaginary loan. It includes:

The company's financial history (3 years of actual figures)
35+ health-check ratios, each with a benchmark and a plain-language comment
A "5 Cs" assessment, a risk matrix and stress tests
A proposed term sheet with covenants, conditions and pricing
Sensitivity grids that show how the results change under different scenarios

2. Why credit analysis matters:

Imagine a friend asks to borrow a large sum from you. Before saying yes, you would check:

Do they earn enough to cover the repayments?	Coverage ratios (interest coverage, DSCR)	Ratio Analysis, section I
Do they already owe too much?	Leverage / gearing	Ratio Analysis, section II
Could they find cash quickly in an emergency?	Liquidity	Ratio Analysis, section III
Are their own customers or debtors paying them back?	Asset quality (NPLs)	Ratio Analysis, section IV
Are they actually profitable?	Profitability	Ratio Analysis, section V
Have they paid people back before?	Character / track record	Risk Assessment (5 Cs)
What if their income suddenly drops?	Stress testing	Risk Assessment and Sensitivity Analysis
What rules should I set so I can step in early?	Covenants	Lending Recommendation

The model answers all eight questions for NCBA, using real published numbers.

Why a bank as the borrower? Banks are analysed differently from ordinary companies. A bank's "debt" is mostly customer deposits, and its "revenue" is mostly interest. So the model uses bank-specific measures such as capital adequacy, loan-to-deposit ratio and non-performing loans alongside the usual coverage and gearing ratios.

The financial data comes from NCBA's public annual reports (FY2023 to FY2025). The loan terms, fees, covenants and the final "approve" decision are my own illustrative choices, made to practise the full credit process end to end

## 3. Plain-English Glossary

| Term | What It Means |
|---|---|
| **Credit memo** | The internal document a bank prepares to justify a lending decision. |
| **Borrower / Lender** | The borrower receives the money and repays it with interest. The lender provides the money. |
| **KES** | Kenyan shillings. The financial sheets are presented in **KES '000** (thousands), so 5,000,000 represents KES 5 billion. |
| **CBR (Central Bank Rate)** | The Central Bank of Kenya's benchmark interest rate. Loan rates may be quoted as CBR plus a margin. **A 10% CBR is assumed for illustration only, not as a forecast.** |
| **Basis points (bps)** | A unit for measuring interest rates. 100 bps = 1 percentage point, so 350 bps = 3.5 percentage points. |
| **Floating rate** | An interest rate that changes with a benchmark rate. In this model, the rate resets quarterly. |
| **Unsecured loan** | A loan without specific collateral. If the borrower defaults, the lender has no pledged asset to claim directly. |
| **Negative pledge** | A contractual promise not to pledge specified assets to other lenders without permission. |
| **Bullet repayment** | A repayment structure in which the principal is repaid in one lump sum at maturity, while interest is paid during the loan term. |
| **Tenor** | The length of time a loan remains outstanding before it matures. |
| **Arrangement fee** | A one-off fee charged for arranging or setting up a loan. |
| **Commitment fee** | A fee charged on committed funds that the borrower has not yet drawn, subject to the loan agreement. |
| **Covenant** | A contractual obligation, such as maintaining a minimum capital ratio. Breaching a covenant may give the lender the right to intervene. |
| **Condition precedent (CP)** | A requirement that must be satisfied before funds can be disbursed, such as signed loan documents or a board resolution. |
| **NOI (Net Operating Income)** | In this bank-analysis model, net operating income refers to net interest income plus fee and other operating income, before operating expenses. This is a model-specific definition. |
| **PAT / PBT** | Profit After Tax / Profit Before Tax. |
| **Interest coverage** | A measure of how many times income covers interest costs. A ratio of 3.86x means the relevant income measure is 3.86 times the interest expense. Higher coverage generally indicates a stronger ability to meet interest obligations. |
| **DSCR (Debt Service Coverage Ratio)** | Cash flow available for debt service divided by principal and interest payments due. A ratio above 1.0x indicates that the measured cash flow exceeds scheduled debt service. |
| **CAR (Capital Adequacy Ratio)** | A bank's regulatory capital relative to its risk-weighted assets. Higher capital adequacy generally provides a larger buffer against losses. |
| **Tier 1 capital** | A bank's core regulatory capital, consisting primarily of high-quality capital such as common equity and retained earnings, subject to regulatory definitions. |
| **NPL (Non-Performing Loans)** | Loans on which borrowers have stopped making required payments or that otherwise meet the applicable non-performing classification criteria. Lower NPL levels generally indicate better asset quality. |
| **Impairment / provisions** | Amounts recognised or set aside to reflect expected credit losses on loans and other financial assets. |
| **Gearing (Debt/Equity)** | A measure of borrowings relative to shareholders' equity. Higher gearing generally indicates greater financial leverage. |
| **Liquidity** |



