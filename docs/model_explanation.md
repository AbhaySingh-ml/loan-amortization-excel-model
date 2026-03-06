# Loan Amortization Financial Model — Detailed Explanation

## 1. Overview

This Excel model calculates loan repayment schedules using financial formulas and visual analytics.

The model helps analyze:

• Monthly EMI payments  
• Principal vs Interest breakdown  
• Loan balance reduction over time  
• Impact of interest rate changes on loan cost

---

## 2. Financial Formula Used

The EMI calculation follows the standard financial formula:

EMI = P × r × (1 + r)^n / ((1 + r)^n − 1)

Where:

P = Loan Amount  
r = Monthly Interest Rate  
n = Total Number of Payments

---

## 3. Amortization Schedule Logic

Each monthly payment is divided into two components:

Interest_t = Opening Balance × Monthly Interest Rate

Principal_t = EMI − Interest_t

Closing Balance_t = Opening Balance − Principal_t

As the loan progresses:

• Interest portion decreases  
• Principal repayment increases

---

## 4. Dashboard Insights

The dashboard provides several analytical views:

Loan Balance Over Time  
Shows how the outstanding balance declines with each EMI payment.

Interest vs Principal Over Time  
Demonstrates how the EMI composition shifts from interest-heavy to principal-heavy.

Loan Cost Breakdown  
Visualizes the proportion of principal and interest in the total repayment.

Interest Rate Sensitivity Analysis  
Analyzes how changes in interest rates affect EMI and total interest paid.

---

## 5. Business Insight

Even small increases in interest rate significantly increase the total cost of borrowing.

Example from the model:

Interest Rate | Total Interest Paid
8% | ₹1,08,291
10% | ₹1,37,411
12% | ₹1,67,333
14% | ₹1,98,047

This highlights the financial impact of interest rate fluctuations.

---

## 6. Tools Used

• Microsoft Excel  
• PMT financial function  
• Excel charts and visualization  
• Amortization schedule modeling
