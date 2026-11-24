# SmartBudget Manager

**An Excel workbook to track your monthly income and expenses, see where your money goes, and get a warning when you exceed your budget.**

Version 1.0 · File: `SmartBudget_Manager.xlsx` · Author of this README: Fayza, 2nd year CPI, ESI-SBA (2026/2027)

## What it does

- Records income and expenses (one transaction per row)
- Sorts expenses into categories: Food, Transport, Rent, Health, Education
- Calculates total income, total expenses and the **monthly balance** automatically
- Shows a pie chart **Expenses by Category**
- Shows **WITHIN BUDGET** (green) or **OVER BUDGET** (red) when you compare spending with your budget

## What you need

| Requirement | Details |
|---|---|
| Software | Microsoft Excel 2016, 2019, 2021, Microsoft 365, or a compatible spreadsheet application |
| File | `SmartBudget_Manager.xlsx` saved on your computer |
| Internet | Not required (no macros, works offline) |
| Skills | Basic Excel: open a file, type in cells, use a drop-down list |

## Get started in 5 steps

1. Double-click `SmartBudget_Manager.xlsx`. If you see **Protected View**, click **Enable Editing**.
2. Open the **Categories** worksheet and set the **Monthly Budget** of each category.
3. Open the **Transactions** worksheet. In the first empty row enter the date, a description, the **Type** (Income / Expense) and, for expenses, the **Category** (use the drop-down list).
4. Type the amount in the **Income** column (money received) or in the **Expense** column (money spent), then press **Enter**.
5. Open the **Dashboard** worksheet to read your totals, the chart and the budget status.

## The three worksheets

| Worksheet | Purpose | Do you type here? |
|---|---|---|
| **Dashboard** | Total income, total expenses, monthly balance, budget status, chart | No (automatic) |
| **Transactions** | Enter every income and expense | Yes (rows 4 to 50) |
| **Categories** | Category list and monthly budgets | Yes (budget amounts) |

## Important rules

- Put the amount in the correct column: **Income** or **Expense**. The **Type** label does not change the totals.
- Choose the category from the drop-down list; a category typed by hand with a spelling error is not counted in the category table or chart.
- Do not type in the **Month** column or on the **Dashboard** (formulas).
- Only rows 4 to 50 (47 transactions) are counted, and totals include all rows: use a new copy of the file for each month.

## Known limitations

- The Dashboard and chart show the first five categories only.
- Spending above the limit of a single category appears as a negative **Remaining** amount (no colour); the colour warning applies to the overall budget.
- Sheets are not password-protected by default. Use **File > Info > Protect Workbook** if needed.

## Documentation and support

- Full instructions: `SmartBudget_User_Guide_Naru_GXX.docx` / `.pdf`
- Requirements: `Software_Requirements_SmartBudget_Naru_GXX.docx`
- Support: [support e-mail] · [phone] (to be completed with the company's contact details)
