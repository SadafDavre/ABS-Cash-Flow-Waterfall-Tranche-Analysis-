ABS Tranche Cash Flow and Yield Model (Excel)


This Excel model simulates cash flow performance and yield metrics for a simplified Asset-Backed Security (ABS) structure with multiple tranches — Senior, Mezzanine, and Equity. It provides a foundation for analyzing risk-return profiles and expected yields under base and stress scenarios.


Overview

The workbook calculates Internal Rate of Return (IRR) and Weighted Average Life (WAL) for each tranche based on projected cash inflows and outflows.
It helps visualize how credit subordination and structural risk impact tranche-level returns and timing of cash recovery.


Key Features

Tranche-Level Modeling
Separate calculations for Senior, Mezzanine, and Equity tranches.

Cash Flow Series (CF Series)
Simulated periodic inflows based on asset repayment assumptions.

IRR and WAL Calculation

IRR (Monthly & Annualized) calculated from cash flow series.

WAL (months) computed from weighted average of principal cash flow periods.

Dynamic Input Section
Editable assumptions to test Base vs. Stress scenarios for repayment, default, or prepayment rates.

Automatic Output Summary
Displays each tranche’s investment, total inflows, IRR, annualized IRR, and WAL for comparison.

How to Use

Open the “Assumptions” tab and adjust starting investment, expected inflows, and repayment periods.

Review the “Portfolio” or “CF Series (for IRR)” section for periodic inflows.

IRR and WAL update automatically based on inputs.

Compare Base vs. Stress scenarios by modifying assumptions.

Example Outputs
Metric	Senior	Mezz	Equity
Initial Investment	-$3,355,856	-$958,816	$0
Sum of Cash Inflows	$3,575,821	$1,178,948	$178,324
IRR (Annualized)	6.17%	9.38%	N/A
WAL (Months)	13	31	—
Purpose

This project demonstrates structured finance fundamentals — yield modeling, risk layering, and timing analysis — using Excel formulas.
It showcases hands-on understanding of ABS tranche mechanics, cash flow modeling, and return sensitivity to stress scenarios.
