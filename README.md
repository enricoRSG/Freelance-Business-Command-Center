# Freelance Business Command Center

**A Google Sheets business management and analytics dashboard for independent professionals and small consulting teams.**

[**View the live Google Sheets demo**](https://docs.google.com/spreadsheets/d/10_H4Upzt9lm3VuXpK4XmF6CoILH6cAsjAm27FL3FFWQ/edit?usp=sharing)

> **Portfolio demonstration** — All client names, email addresses, projects, timesheets, and invoices are synthetic. This is not a live business or accounting system.

## Overview

Freelance Business Command Center brings together client records, project information, time tracking, and invoice monitoring in a single spreadsheet-based workflow. A dashboard summarizes the most important operational metrics.

## Features

- **Client directory:** eight fictional business clients with industry, contact, and country fields.
- **Project management:** 24 example engagements, with hourly rates, planned hours, and project status.
- **Time tracking:** 96 sample time entries; billable value is calculated using project rates.
- **Invoice tracking:** 30 example invoices with payment status, invoice amounts, and due dates.
- **KPI dashboard:** client and project counts, tracked hours, billable value, collected payments, and overdue balances.
- **Monthly chart:** trends in billable value by month.

## Workbook tabs

| Tab | Purpose |
| --- | --- |
| `Clients` | Client master data |
| `Projects` | Engagement details and pricing |
| `Timesheets` | Hours and formula-calculated billable values |
| `Invoices` | Invoicing and payment statuses |
| `Dashboard` | Key metrics and monthly visualization |
| `Guide` | Usage notes and assumptions |

## Technology and spreadsheet skills

Google Sheets, spreadsheet modeling, `VLOOKUP`, `SUMIF`, `COUNTIF`, linked tables, KPI calculations, and chart-based reporting.

## Try it

1. Open the [Google Sheets demonstration](https://docs.google.com/spreadsheets/d/10_H4Upzt9lm3VuXpK4XmF6CoILH6cAsjAm27FL3FFWQ/edit?usp=sharing) (shared as view-only).
2. Review the `Dashboard` and explore the other five tabs.
3. To experiment with editing data, create your own copy using **File → Make a copy** (if permitted) or download the Excel workbook from this repository and import it into Google Sheets.
4. In the `Timesheets` tab, change sample hours: `Billable value EUR` should update. In `Invoices`, change a payment status to `Paid`: `Collected EUR` should update.

## Files

- [`01_Freelance_Business_Command_Center.xlsx`](01_Freelance_Business_Command_Center.xlsx) — downloadable spreadsheet workbook.
- `README.md` — project overview, features, and reproduction instructions.

## Scope and limitations

- The data are entirely fictional and intended for demonstrations only.
- Source formulas use bounded ranges; they should be expanded for larger datasets.
- The invoice status field is manually maintained; no bank feed, payment integration, or automatic overdue-status calculation is included.
- Billable amounts and collections are separate metrics and should not be interpreted as audited revenue or profit.
- This project does not use Google Apps Script or third-party APIs.
- Initial functional checks of three reactive metrics were completed in Google Sheets; a full production-quality validation has not been performed.

## Portfolio context

Developed as part of a practical Google Sheets learning portfolio, alongside Retail Sales Intelligence and Smart Inventory Control.
