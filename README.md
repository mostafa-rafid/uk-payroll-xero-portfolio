End-to-End UK Payroll Processing & HMRC Statutory Compliance Portfolio

An enterprise-grade demonstration of UK payroll administration, statutory HMRC tax compliance, workplace pension auto-enrolment, and general ledger financial integration executed within Xero Payroll.

1. Executive Summary & Portfolio Overview

This repository showcases a comprehensive UK payroll project covering an active 8-employee workforce. Operating under UK tax legislation for Tax Year 2025/26 (Tax Month 12, week ending 07 March 2026), this project demonstrates practical expertise in cloud payroll software administration (Xero Payroll with secondary QuickBooks Online preview verification), statutory deductions processing, HMRC payment reconciliation, and double-entry accounting integration.

The project models the full operational cycle of UK payroll, from employee onboarding and tax code assignment through weekly pay run execution, monthly employer liability consolidation (P32 Employer Payment Record), and end-of-year statutory reporting (eP60 Certificates).

Core Operational Metrics (Pay Period 01/03/2026 – 07/03/2026)

* Gross Workforce Compensation: £5,615.93
* PAYE Income Tax Deducted: £571.78
* Employee Primary Class 1 National Insurance: £267.18
* Workplace Pension Employee Deductions (NEST): £174.93
* Net Salary Disbursement: £4,602.04
* Employer Secondary Class 1 National Insurance: £713.68
* Total Employment Overhead Cost: £6,329.61 (£5,615.93 Gross Earnings + £713.68 Employer NI)

2. 3-Tier Payroll Framework Architecture

To provide a complete framework for payroll governance, the repository is structured across three distinct operational levels:

                               ┌────────────────────────────────────────┐
                               │  LEVEL 1: WEEKLY PAY RUN OPERATIONS    │
                               │  - Xero Payroll Execution              │
                               │  - Gross-to-Net Calculations           │
                               │  - Varied Tax Codes & Pension Rules    │
                               └───────────────────┬────────────────────┘
                                                   │
                                                   ▼
                               ┌────────────────────────────────────────┐
                               │  LEVEL 2: MONTHLY STATUTORY REPORTING  │
                               │  - P32 Employer Payment Summaries      │
                               │  - HMRC PAYE / Class 1 NIC Liability   │
                               │  - P&L and Balance Sheet Posting       │
                               └───────────────────┬────────────────────┘
                                                   │
                                                   ▼
                               ┌────────────────────────────────────────┐
                               │  LEVEL 3: END-OF-YEAR COMPLIANCE       │
                               │  - eP60 Certificates Generation        │
                               │  - Cumulative Tax & Pay Reconciliation │
                               │  - HMRC Statutory Audit Trail          │
                               └────────────────────────────────────────┘


1. Level 1: Operational Pay Run Execution: Processing weekly timesheets, allowances, overtime rates, night shift premiums, and calculating gross-to-net salary disbursements for 8 employees.
2. Level 2: Monthly Statutory Consolidation & Ledger Reconciliation: Aggregating weekly tax withholdings and employer contributions into HMRC P32 Employer Payment Summaries and mapping payroll obligations directly to Profit & Loss and Balance Sheet accounts.
3. Level 3: Year-End Tax Certification: Reconciling cumulative annual pay and tax figures to issue statutory eP60 End of Year Certificates for all workforce members at tax year-end.

3. Master Workforce Payroll Roster & Weekly Pay Run Breakdown

The workforce consists of 8 active employees on a weekly pay cycle ending 07 March 2026. The table below details the full breakdown of earnings, statutory withholdings, pension contributions, net payments, and employer liabilities:

Employee Name	Payroll ID	Tax Code & Basis	NI Category	Gross Pay	PAYE Tax	EE NI	NEST EE Pension	Net Pay	Employer NI
A LAWRENCE	    168         	1237L(Cumulative)	A	       £720.00	 £96.80	  £38.24 £28.80	£556.16	£93.60
Brian MCCAFFERTY	086	1231L (Cumulative)	A	£690.30	£85.60	£33.86	£0.00	£570.84	£85.39
G ERRINGTON	145	1237L (Cumulative)	A	£973.00	£147.00	£58.12	£38.92	£728.96	£131.55
I MILLER	221	K163 (Cumulative)	A	£497.50	£103.80	£0.00	£0.00	£393.70	£58.72
J IRVING	213	1257L (Cumulative)	A	£388.78	£27.40	£10.94	£15.15	£335.29	£42.42
J G COOK	116	1257L (Cumulative)	A	£720.80	£90.80	£36.30	£27.83	£565.87	£89.97
T I DUFF	205	S1207L (Scottish)	A	£888.40	£146.55	£51.71	£35.54	£654.60	£118.86
Tony ROBERTSHAW	004	1257L (Cumulative)	A	£737.15	-£126.17	£38.01	£28.69	£796.62	£93.17
WORKFORCE TOTALS	—	—	—	£5,615.93	£571.78	£267.18	£174.93	£4,602.04	£713.68

Detailed Component Analysis

* Earnings Structure: Total gross compensation of £5,615.93 comprises regular hourly wages (£1,568.00), day shift units (£1,304.88), night shift premiums (£503.20), Saturday units (£478.85), Sunday units (£195.80), accrued holiday pay (£1,334.20), performance bonuses (£141.00), and non-taxable expense reimbursements (£90.00).
  
* PAYE Tax Refunds: Tony Robertshaw (1257L Cumulative) received a PAYE tax refund of £126.17 during Tax Month 12 due to cumulative tax recalculation against total year-to-date earnings (£34,874.80) and tax previously paid (£4,378.83).
  
* Specialist K-Code Rules: I Miller (K163 Cumulative) possesses negative personal allowance, requiring tax collection on £1,630 of additional untaxed annual income spread across pay periods, resulting in £103.80 PAYE tax on £497.50 gross pay.

* Scottish Tax Regime: T I Duff operates under Scottish Tax Code S1207L (Scottish Starter, Basic, and Intermediate Tax Bands), requiring localized PAYE calculation (£146.55 tax on £888.40 gross earnings).

4. Statutory Compliance & Pension Mechanics

Tax Code & NI Configuration Analysis

1. Standard Personal Allowance (1257L / 1237L / 1231L): Reflects standard UK personal allowance allowances (£12,570 annually) adjusted for individual HMRC notice changes (e.g., £12,370 for 1237L or £12,310 for 1231L).
2. K-Codes (K163): Used when taxable benefit-in-kind values or state benefits exceed the standard personal allowance, creating a net negative allowance where tax is added to gross pay before applying tax bands.
3. Scottish Tax Rules (S1207L): Applied to Scottish tax residents, applying Scottish Income Tax thresholds across Starter (19%), Basic (20%), Intermediate (21%), and Higher (42%) rates.
4. National Insurance Category A: Standard rate Category A applied across all employees. EE NI is calculated at 8% on earnings above the Primary Threshold (£242/week), while ER NI is calculated at 13.8% on earnings above the Secondary Threshold (£175/week).
5. Auto-Enrolment Workplace Pension (NEST): Configured under qualifying earnings thresholds. Eligible employees contribute 5% employee pension (totaling £174.93 across active participants).

5. Financial Ledger & General Ledger Double-Entry Integration

Payroll processing triggers automated general ledger postings across operational expense accounts and liability clearing accounts.

Profit & Loss Statement Impact

Payroll expenses are recognized within Administrative Overhead for the financial period ending April 2026:

* Salaries & Wages Expense: £5,615.93
* Employer National Insurance Expense: £713.68
* Total Operating Employment Overhead: £6,329.61

Balance Sheet Liability Accounts (As at Month-End)

* Wages Payable (Net Pay Clearing): £6,377.90
* NIC Payable (HMRC Liability): £980.86 (£267.18 Employee NI + £713.68 Employer NI)
* Pensions Payable (NEST Clearing): £174.93
* PAYE Payable: -£1,204.08 (Adjusted for cumulative tax refunds and prior month clearing entries)
* Net Current Liabilities Impact: £6,329.61

6. Repository Structure & Confidentiality Guidelines

uk-payroll-xero-portfolio/
│
├── README.md                          <-- Portfolio Documentation & Project Overview
├── docs/
│   ├── payroll-summary-report.pdf     <-- Anonymized Xero Payroll Summary
│   ├── payroll-activity-details.pdf   <-- Itemized Employee Earnings Ledger
│   ├── p32-employer-summary.pdf       <-- HMRC P32 Employer Payment Record
│   ├── sample-xero-payslips.pdf       <-- Redacted Weekly Payslips (March 2026)
│   └── ep60-annual-certificates.pdf   <-- Redacted Year-End P60 Certificates
├── accounting/
│   ├── profit-and-loss-report.pdf     <-- P&L Payroll Overhead Mapping
│   ├── balance-sheet-statement.pdf    <-- Balance Sheet Liability Accounts
│   └── transaction-journal.pdf        <-- Double-Entry Ledger Journal Entries
└── cross-verification/
    ├── qbo-payroll-preview.pdf        <-- QuickBooks Online Secondary Audit Check
    └── qbo-sample-payslips.pdf        <-- QBO Monthly Payslip Format Verification


Anonymization & Data Protection Protocol

To comply with GDPR and confidentiality guidelines:

* Company names have been anonymized (Haulage Express Ltd / Apex Sports Ltd).
* National Insurance numbers are masked in visual displays (JS89****A).
* Residential street addresses and personal contact info have been redacted on all public PDF documentation.
* HMRC PAYE and Accounts Office Reference numbers are sanitized.

7. Audit, Verification & Replication Steps

To verify the calculations in Xero Payroll:

1. Reconcile Weekly Gross-to-Net: Sum individual employee earnings from docs/payroll-activity-details.pdf and verify against docs/payroll-summary-report.pdf (£5,615.93 Gross, £4,602.04 Net).
2. Audit P32 Liability: Compare Class 1 NIC (£980.86) and PAYE (£571.78) against the Month 12 totals in docs/p32-employer-summary.pdf.
3. Verify General Ledger Postings: Confirm that total employment costs (£6,329.61) match the Administrative Costs posted in accounting/profit-and-loss-report.pdf and the corresponding liability clearing accounts in accounting/balance-sheet-statement.pdf.

