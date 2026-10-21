# Expense Tracker

A mobile-first expense tracker I built for myself and use day to day. This public version runs on fictional sample data.

**Live demo:** https://nicolasmiodownik.github.io/expense-tracker/

## The problem

Most expense apps show you a long list of transactions. I didn't want a list. I wanted to answer three questions in ten seconds:

1. How much have I spent this month, and am I above or below last month at this same point?
2. Where is the money going?
3. Where will I close the month if I keep this pace?

## What it does

- **Fast logging.** Amount, payment method and category in three taps, with one-tap subcategories. No typing needed.
- **Monthly overview.** Month to date, daily average and an end-of-month projection. The projection counts fixed costs (rent, utilities, subscriptions) once and only extrapolates variable spending, so it doesn't overshoot early in the month.
- **Fair comparison.** This month is compared with last month up to the same day, not with the full month.
- **Automatic insights.** Flags when spending is concentrated in one category, a recurring habit (like delivery), a jump vs. last month, or a payment method that dominates.
- **Trend and payment mix.** Six-month trend and spend by payment method.
- **Photo capture.** In my own version, a photo of a receipt goes into a queue and an AI reads amount, method and category. In this demo the photo stays in the browser and is not processed.

## How it's built

A single HTML file with plain JavaScript, no framework and no backend. The demo stores data in the browser's `localStorage`, generates the sample data on load, and has export (JSON) and reset options.

## What's next

- Monthly budgets per category with alerts.
- Process receipt photos automatically in the public version.
- Shared expenses between two people.

## Built by

Nicolás Miodownik. I build the tools I need with AI coding tools, which is how I prototype most of my ideas.
