---
type: source
original: "[[Clippings/Mastering Spreadsheets — Expense Tracker — Rafael Makino.md]]"
author: "Rafael Makino"
published: 2024-01-01
ingested: 2026-05-19
tags: [google-sheets, tools, systems, productivity, budgeting]
---

# Mastering Spreadsheets — Smart Expense Tracker in Google Sheets (Rafael Makino)

> GoGet'Em Community tutorial: build a fully automated Google Sheets expense tracker with dropdown menus, pivot tables, conditional formatting, and auto-updating charts.

## Key Takeaways

- **Headers**: Date, Description, Category, Amount, Payment Method → bold → freeze Row 1 → add all borders
- **Dropdown menus**: right-click cell → Add Dropdown → add categories (transport, food, shopping, online shopping) and payment methods (credit card, debit card, cash) → drag dot down to apply to all rows
- **Currency format**: highlight Amount column → Format as Currency
- **Pivot Table**: Insert → Pivot Table → New Sheet → add Amount to Values, Category to Rows → auto-sums spending by category → updates automatically as new expenses are added
- **Conditional Formatting**: highlight Amount column → right-click → Conditional Formatting → "Greater than or equal to" → enter threshold (e.g. $350) → set fill color red → highlights big expenses automatically
- **Chart**: highlight all data → Insert → Chart → change to Pie Chart → set Values = Amount, dimension = Category → check "Aggregate" to combine same-category expenses → chart updates automatically
- Challenge: try this today with your own expenses — fully automated expense view without manual work

## Quotes

> "The best part is just in a few minutes we built a whole spreadsheet that calculates totals automatically, breaks down spending by category, highlights important numbers, generates charts for quick insights."

## Wiki Pages Updated

- [[Productivity Tools and Systems]] — added Google Sheets expense tracker
