# Credit Analysis Case Study: KES 5 Billion Loan

An illustrative learning project based on publicly available annual reports. This is not a real credit decision. The “Hypothetical Lender” is fictional. I am not affiliated with NCBA Group PLC, and this project does not constitute investment, credit or legal advice.

Table of Contents: 
1. What Is This Project?
2. Why Credit Analysis Matters
3. Plain-English Glossary
4. The Proposed Loan
5. Sheet-by-Sheet Guide
6. How the Analysis Works
7. Key Findings
8. Stress Tests and Sensitivity Tables
9. Two Kinds of Interest Coverage
10. Assumptions
11. Known Limitations
12. How to Use the Workbook
13. Ideas for Extending the Project
14. Skills Demonstrated
15. Disclaimer
    
1. What Is This Project?
   
When a company asks a bank for a large loan, the bank's credit team writes a credit memo. It is a structured document that answers one question:

"If we lend this money, will we get it back and are we paid enough for the risk?"

This project is an illustrative credit memo for a hypothetical loan. It includes:
- Three years of historical financial data.
- More than 35 financial ratios, each with a benchmark and plain-English assessment.
- A 5 Cs of Credit assessment, a risk matrix, and stress tests.
- A proposed term sheet covering covenants, conditions, and pricing.
- Sensitivity tables showing how results change under different scenarios.
  
2. Why Credit Analysis Matters
   
Imagine a friend asks to borrow a large sum from you. Before saying yes, you would check:
- Credit question	What to analyse	Where it appears in the workbook
- Can they cover repayments?	Interest coverage and DSCR	Ratio Analysis, Section I
- Do they already owe too much?	Leverage and gearing	Ratio Analysis, Section II
- Can they access cash in an emergency?	Liquidity	Ratio Analysis, Section III
- Are their borrowers repaying?	Asset quality and NPLs	Ratio Analysis, Section IV
- Are they profitable?	Profitability	Ratio Analysis, Section V
- Do they have a reliable repayment track record?	Character and track record	Risk Assessment, 5 Cs
- What if income suddenly drops?	Stress testing	Risk Assessment and Sensitivity Analysis
- What rules would allow early intervention?	Covenants	Lending Recommendation


The model answers all the questions for NCBA, using real published numbers.

Why a bank as the borrower? Banks are analysed differently from ordinary companies. A bank's "debt" is mostly customer deposits, and its "revenue" is mostly interest. So the model uses bank-specific measures such as capital adequacy, loan-to-deposit ratio and non-performing loans alongside the usual coverage and gearing ratios.

The financial data is drawn from NCBA's public annual reports for FY2023–FY2025. The loan terms, fees, covenants, and illustrative approval decision are assumptions created for this learning project.

3. Plain-English Glossary:
   
Term	What It Means
Credit memo	The internal document a bank prepares to justify a lending decision.
Borrower / Lender	The borrower receives the money and repays it with interest. The lender provides the money.
KES	Kenyan shillings. The financial sheets are presented in KES '000 (thousands), so 5,000,000 represents KES 5 billion.
CBR (Central Bank Rate)	The Central Bank of Kenya's benchmark interest rate. Loan rates may be quoted as CBR plus a margin. A 10% CBR is assumed for illustration only, not as a forecast.
Basis points (bps)	A unit for measuring interest rates. 100 bps = 1 percentage point, so 350 bps = 3.5 percentage points.
Floating rate	An interest rate that changes with a benchmark rate. In this model, the rate resets quarterly.
Unsecured loan	A loan without specific collateral. If the borrower defaults, the lender has no pledged asset to claim directly.
Negative pledge	A contractual promise not to pledge specified assets to other lenders without permission.
Bullet repayment	A repayment structure in which the principal is repaid in one lump sum at maturity, while interest is paid during the loan term.
Tenor	The length of time a loan remains outstanding before it matures.
Arrangement fee	A one-off fee charged for arranging or setting up a loan.
Commitment fee	A fee charged on committed funds that the borrower has not yet drawn, subject to the loan agreement.
Covenant	A contractual obligation, such as maintaining a minimum capital ratio. Breaching a covenant may give the lender the right to intervene.
Condition precedent (CP)	A requirement that must be satisfied before funds can be disbursed, such as signed loan documents or a board resolution.
NOI (Net Operating Income)	In this bank-analysis model, net operating income refers to net interest income plus fee and other operating income, before operating expenses. This is a model-specific definition.
PAT / PBT	Profit After Tax / Profit Before Tax.
Interest coverage	A measure of how many times income covers interest costs. A ratio of 3.86x means the relevant income measure is 3.86 times the interest expense. Higher coverage generally indicates a stronger ability to meet interest obligations.
DSCR (Debt Service Coverage Ratio)	Cash flow available for debt service divided by principal and interest payments due. A ratio above 1.0x indicates that the measured cash flow exceeds scheduled debt service.
CAR (Capital Adequacy Ratio)	A bank's regulatory capital relative to its risk-weighted assets. Higher capital adequacy generally provides a larger buffer against losses.
Tier 1 capital	A bank's core regulatory capital, consisting primarily of high-quality capital such as common equity and retained earnings, subject to regulatory definitions.
NPL (Non-Performing Loans)	Loans on which borrowers have stopped making required payments or that otherwise meet the applicable non-performing classification criteria. Lower NPL levels generally indicate better asset quality.
Impairment / provisions	Amounts recognised or set aside to reflect expected credit losses on loans and other financial assets.
Gearing (Debt/Equity)	A measure of borrowings relative to shareholders' equity. Higher gearing generally indicates greater financial leverage.
Liquidity	The ability to meet financial obligations when they fall due. Banks manage liquidity using cash, liquid securities and other available funding sources.
LDR (Loan-to-Deposit Ratio)	Loans divided by deposits. A lower ratio may indicate greater deposit funding headroom, but interpretation depends on the bank's liquidity position and business model.
NIM (Net Interest Margin)	Net interest income divided by average interest-earning assets. It measures how effectively a bank earns interest income relative to its funding costs and interest-earning assets.
ROE / ROA	Return on Equity / Return on Assets. ROE measures profit relative to shareholders' equity, while ROA measures profit relative to total assets.
Cost-to-income ratio	Operating expenses divided by operating income. A lower ratio generally indicates greater operating efficiency.
Stress test	An assessment of how a borrower or bank performs under adverse scenarios, such as lower income, higher funding costs or increased credit losses.
Sensitivity analysis	An analysis showing how changes in one or more assumptions affect a financial result.
RAROC (Risk-Adjusted Return on Capital)	Risk-Adjusted Return on Capital. It assesses whether the return generated is sufficient relative to the capital required to support the associated risk.
5 Cs of Credit	A traditional credit assessment framework: Character, Capacity, Capital, Collateral and Conditions.


5. The Proposed Loan
Item	Detail
Borrower	NCBA Group PLC, the parent company listed on the Nairobi Securities Exchange
Lender	Hypothetical Lender (placeholder, not a real institution)
Facility	Senior unsecured bilateral term loan
Amount	KES 5,000,000,000 (KES 5 billion), approximately 3.9% of NCBA's equity of KES 127.4 billion
Tenor	36 months from first drawdown
Availability period	6 months to draw the funds after signing
Drawdowns	Minimum KES 500 million per drawdown, with a maximum of 3 drawdowns
Repayment	Bullet repayment at maturity, with interest paid quarterly
Interest rate	CBR + 350 basis points (bps), floating and reset quarterly; 13.5% per annum at an assumed CBR of 10%
Default interest	Contractual interest rate + 300 bps on overdue amounts
Arrangement fee	1.00% of the facility amount (KES 50 million)
Commitment fee	0.50% per annum on undrawn amounts during the availability period
Prepayment	Permitted without penalty on 30 days' notice
Security	Unsecured, with a negative pledge
Purpose	General corporate purposes, working capital and funding subsidiaries
Governing law	Laws of Kenya


Estimated interest payments: At an illustrative annual interest rate of 13.5% on KES 5 billion, annual interest would be approximately KES 675 million, or KES 168.75 million per quarter, assuming the full principal remains outstanding and the rate stays unchanged.
5. Sheet-by-Sheet Guide
#	Sheet	What It Does	Read It If You Want to...
1	Credit Memo	Presents the loan summary, executive summary and workbook navigation.	Understand the overall lending recommendation in approximately 2 minutes.
2	Borrower Profile	Covers NCBA's business model, revenue sources, ownership, management and governance.	Understand the borrower and how the company operates.
3	Financial Statements	Presents three years of income statement, balance sheet and cash flow figures, including two-year growth rates.	Review the historical financial performance and position.
4	Ratio Analysis	Analyses 35+ financial ratios across six categories, with benchmarks and concise assessments.	Understand what the financial numbers indicate about performance and risk.
5	Risk Assessment	Applies the 5 Cs of Credit, a 10-item risk matrix and a covenant-breach stress table.	Identify key credit risks and potential downside scenarios.
6	Lending Recommendation	Sets out the lending decision, proposed term sheet, covenants, conditions precedent, pricing and approvals.	Review the proposed transaction and lending conditions.
7	Sensitivity Analysis	Includes three scenario grids covering facility coverage, profitability under loan losses, and DSCR under combined stress.	Test how adverse assumptions could affect the lending decision.
8	Sources and Assumptions	Documents source reports, modelling assumptions, a revenue cross-check and coverage-ratio definitions.	Verify the model's inputs, methodology and calculations.


Ratio Analysis Sections
I. Debt service and coverage: can earnings and cash flow cover interest and repayments?
II. Leverage and capital: how much debt, and how big is the capital cushion?
III. Liquidity: can NCBA find cash quickly?
IV. Asset quality: are NCBA's own borrowers repaying?
V. Profitability: how well does NCBA turn assets and equity into profit?
VI. Credit-specific banking ratios: single-borrower limit, related-party lending, foreign currency exposure.
6. How the Analysis Works
Step 1: Gather the financial statements
Three years of figures (FY2023, FY2024, FY2025) go into the Financial Statements sheet. Growth rates are calculated with live formulas. For example, NCBA's net interest income grew from KES 38.2 billion in FY2023 to KES 57.7 billion in FY2025.
Step 2: Turn the numbers into ratios
Raw numbers are hard to judge on their own, so ratios compare one number with another. A few examples using NCBA's FY2025 figures:
Ratio	Calculation	Result	Meaning
Gearing	Borrowings ÷ equity = 7.6bn ÷ 127.4bn	5.9%	Almost no debt relative to owners' funds.
Loan-to-deposit	Loans ÷ deposits = 306.9bn ÷ 531.9bn	57.7%	The bank lends out well under two-thirds of its deposits.
Liquidity	(Cash + government securities) ÷ deposits = (63.8bn + 221.6bn) ÷ 531.9bn	53.7%	More than half of deposits are backed by cash or government bonds.
Cost-to-income	Operating costs ÷ income = 37.1bn ÷ 71.8bn	51.7%	About KES 52 of every KES 100 earned goes toward running costs.
Equity ÷ assets	127.4bn ÷ 716.0bn	17.8%	A substantial equity cushion relative to total assets.


Each ratio is compared with a benchmark (for example, liquidity of at least 20%), and a short comment says whether it passes. The "Assessment" column is written for a reader who doesn't want to re-derive anything.
Step 3: Judge the borrower on the 5 Cs
The Risk Assessment sheet scores NCBA on the classic checklist:
C	Question	Rating in This Case Study
Character	Is the borrower honest, transparent and reliable?	Strong
Capacity	Can it repay from its earnings?	Strong
Capital	Does it have a financial cushion?	Very strong
Collateral	What can the lender claim if things go wrong?	Moderate (the loan is unsecured, so the decision rests on cash flow)
Conditions	How are the economy and industry?	Moderate (the CBK rate cycle and sector bad loans are watch points)


Step 4: Map the risks
A risk matrix rates 10 risks by how likely they are and how much damage they would do. One is rated High (credit and NPL risk), six Medium (interest rate, liquidity, refinancing, concentration, operational, sovereign) and three Low (regulatory, foreign exchange, reputational). Each has a stated mitigation.
Step 5: Design the deal
The Lending Recommendation sheet turns the analysis into a term sheet:
- Covenants: Financial rules the borrower must keep. Examples: CAR of at least 15.5%, group interest coverage of at least 2.50×, DSCR of at least 1.20×, NPL ratio no higher than 10%. Each is shown next to NCBA's actual FY2025 figure and the headroom (the safety gap).
- Conditions precedent: Ten boxes to tick before any cash is paid out, such as board resolutions, legal opinions and KYC checks.
- Pricing: The 350 bps margin is built up from risk adjustments. Being unsecured adds 100 bps and the 3-year tenor adds 75 bps. Strong credit quality takes off 25 bps and the relationship takes off 50 bps. A 250 bps market-standard floor brings the total to 350 bps. The sheet also shows illustrative comparable deals, an estimated RAROC of 18–22% against an internal hurdle of 15%, and a break-even loss rate.
- Approvals: Who must sign off at each level of the credit chain.
Step 6: Stress It
The final step asks, "What if income falls?" The next section explores the results of these stress scenarios.
7. Key Findings
Check	NCBA FY2025	Loan Requirement	Verdict
Profit after tax	KES 23.4bn (+7.0% on FY2024)	N/A	Strong. Roughly 4.7 times the loan amount.
Group interest coverage	3.86×	At least 2.50×	Pass
Debt service coverage (DSCR)	1.66×	At least 1.20×	Pass
Capital adequacy (CAR)	19.8%	At least 15.5%	Pass (4.3 percentage points of headroom)
Tier 1 capital ratio	16.3%	At least 12.0%	Pass
Gearing (debt ÷ equity)	0.06×	At most 0.50×	Pass
Liquidity (cash + government bonds ÷ deposits)	53.7%	At least 30%	Pass
Return on assets (ROA)	About 3.3%	At least 1.5%	Pass
Bad loans (NPL ratio)	About 7.5% (down from 8.6%)	At most 10%	Pass, but the main watch point


Case for Approval
The illustrative case for approval rests on strong and growing profits, a substantial liquidity buffer, low reported borrowings relative to equity, capital above the model's threshold, and a proposed facility that is small relative to the balance sheet.
Main Credit Concerns
- Asset quality: The NPL ratio of approximately 7.5% is above the model's 5% benchmark and is the weakest ratio highlighted.
- Provision coverage: Loan-loss reserve coverage is 61%, below the model's 70% benchmark, which may indicate a need for additional provisions.
- Unsecured exposure: The lender has no specific collateral to claim if the borrower defaults. Recovery would depend on available assets and the applicable legal ranking.
- Slowing earnings growth: PAT growth declined from 20.8% in FY2024 to 7.0% in FY2025.
8. Stress Tests and Sensitivity Tables
Stress Test (Risk Assessment, Section C)
The stress test reduces the bank's income by different amounts to assess when the proposed financial covenants would be breached.
Scenario	Group Interest Coverage (Min. 2.50×)	DSCR (Min. 1.20×)	Breach?
Base case (FY2025 actual)	3.86×	1.66×	No
Mild: NOI −10%	3.48×	1.49×	No
Moderate: NOI −20%	3.09×	1.33×	No
Severe: NOI −30%	2.70×	1.16×	Yes (DSCR)
Extreme: NOI −50%	1.93×	0.83×	Yes (both covenants)
NPL surge: +5 percentage points of extra impairment	3.04×	0.93×	Yes (DSCR)


Key takeaway: In this model, NCBA can withstand an income decline of approximately 20% without breaching either covenant. Under the 30% decline scenario, the DSCR falls below the minimum requirement of 1.20×, potentially giving the lender the right to intervene under the loan agreement.
Sensitivity Analysis
Table	What Changes	What It Shows
Table 1: Facility Interest Coverage	NOI declines by 0–30%, while the interest rate ranges from CBR + 200 bps to CBR + 500 bps.	Shows how changes in income and interest rates affect the borrower's ability to cover interest on the proposed loan alone.
Table 2: PAT Under Loan Losses	NPL ratio ranges from 5–18%, against a loss-given-default (LGD) range of 30–60%.	Intended to show how profitability changes as non-performing loans and expected credit losses increase. Currently displays zeros; see model limitations.
Table 3: DSCR Under Combined Stress	NOI declines by 0–30%, with additional impairment ranging from KES 0–12 billion.	Shows which combinations of declining income and additional credit losses cause the DSCR to breach the 1.20× covenant.


9. Two Kinds of Interest Coverage
The model presents two interest coverage figures that may initially appear inconsistent: 3.86× and approximately 106×. They are intended to measure different things.
	Group Interest Coverage	Facility Interest Coverage
Question	Can NCBA's income cover all the interest it pays?	Can NCBA's income cover interest on the proposed loan alone?
Formula stated in the model	NOI ÷ all of NCBA's finance costs	NOI ÷ (KES 5bn × 13.5%)
FY2025 result	3.86×	Approximately 106×
Where it appears	Ratio Analysis, Risk Assessment, and covenant test	Sensitivity Analysis, Table 1


The facility-level figure is much higher because the proposed loan is small relative to NCBA's overall funding costs. It is intended to show the relative size of the new facility, not the bank's overall creditworthiness. The model uses group interest coverage for the covenant test.
Validation note: Confirm that the income numerator used for the approximately 106× facility coverage calculation matches the formula shown in the workbook. The numerator and the model's definition of NOI should be consistent.

10. Assumptions
All inputs are documented on the Sources and Assumptions worksheet. Blue cells are intended to be editable inputs; linked formulas should update when those inputs change.
Assumption	Value
Central Bank Rate (CBR)	10.0% (illustrative, not a forecast)
Credit margin	3.50% (350 bps)
All-in interest rate	13.50% per annum
Facility amount	KES 5,000,000 thousand (KES 5bn)
Tenor	36 months
Availability period	6 months
Arrangement fee	1.00% of the facility, charged once (KES 50 million)
Commitment fee	0.50% per annum on undrawn amounts during the availability period
Default margin	+3.00% on overdue amounts


Illustrative Year-1 Revenue Check
Amounts below are in KES millions.
Revenue Component	Calculation	Amount (KES million)
Interest income	KES 5,000m × 13.50%	675.0
Arrangement fee	KES 5,000m × 1.00%	50.0
Commitment fee	KES 5,000m × 0.50% × 6 ÷ 12	12.5
Total Year-1 revenue	Interest + arrangement fee + commitment fee	737.5


The total of KES 737.5 million is the illustrative figure stated in the Lending Recommendation worksheet.
Validation note: The commitment-fee calculation assumes the full KES 5bn remains undrawn for the entire six-month availability period. If drawdowns occur during that period, the fee should be calculated on the actual undrawn balance over time. Confirm that the workbook's fee formula reflects the intended drawdown assumptions.

11. Known Limitations
- Illustrative transaction: The lender, loan terms, pricing, covenants, and approval recommendation are hypothetical.
- Sensitivity table limitation: Table 2, “PAT Under Loan Losses,” currently displays zeros and should not be relied on until the formulas and inputs are checked.
- Model-dependent definitions: Some measures, including NOI, coverage ratios, and stress-test mechanics, follow definitions used in this workbook and may differ from standard bank or lender methodologies.
- Assumptions and rounding: Figures may be rounded, and assumptions may materially affect the outputs.
- Independent validation required: The workbook has not been presented as a validated model for a real lending decision.
12. How to Use the Workbook
1. Start with the Credit Memo sheet for the transaction summary and recommendation.
2. Review Borrower Profile and Financial Statements to understand the borrower and historical figures.
3. Use Ratio Analysis to review performance, capital, liquidity, asset quality, and coverage.
4. Read Risk Assessment and Lending Recommendation to understand the risks, proposed covenants, conditions, and decision.
5. Review Sensitivity Analysis to test how selected assumptions affect the outputs.
6. Check Sources and Assumptions to trace inputs and definitions. Change only intended input cells, shown in blue, and confirm that linked formulas update as expected.
13. Ideas for Extending the Project
- Repair and validate the PAT-under-loan-losses sensitivity grid.
- Add a clearer downside case for funding costs, credit losses, and capital adequacy.
- Add a source register mapping each historical figure to the relevant annual-report page.
- Add model checks for balance-sheet balancing, formula integrity, and sensitivity-grid outputs.
- Compare the illustrative facility with alternative loan structures, pricing, and repayment profiles.
14. Skills Demonstrated
- Financial statement analysis
- Credit risk assessment and the 5 Cs of Credit
- Financial ratio analysis and benchmarking
- Loan structuring, pricing, and covenant design
- Stress testing and sensitivity analysis
- Excel financial modelling and assumption management
- Translating financial outputs into a concise credit recommendation
15. Disclaimer
For educational purposes only. This case study uses figures described as being drawn from publicly available annual reports and includes hypothetical transaction assumptions. It is not affiliated with, endorsed by, or connected to NCBA Group PLC or any financial institution. No confidential or employer material is intended to be used. Figures and calculations may contain errors. Do not use this project to make real lending, investment, or legal decisions.




## 3. Plain-English Glossary

