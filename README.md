# Paytm Payday Hub — mobile prototype

An independent Paytm-inspired concept for planning monthly obligations, recording simulated payments and reviewing spending.

## Try it

Open `index.html` in a browser. All styles and scripts are included in the file; no installation or build is required.

## Main flow

Paytm Home → Payday Hub → recorded salary, planned monthly obligations and outstanding cues → choose a payment → review recipient and bank → simulate payment → receipt → return to the updated Hub or Spend Summary.

The presentation includes a phone boundary, time, signal, Wi-Fi and charging battery icons. The app also supports shared tags, reminders, paid-elsewhere records, dated recurring occurrences and illustrative AutoPay visibility. Demo state saves in the current browser.

## Important boundaries

This is not an official Paytm product or integration and is not affiliated with or endorsed by Paytm. Names, accounts, income, balances and transactions are fictional. No money moves; no real UPI PIN, bank, SMS, camera or location access is requested. Reminder schedules do not send notifications. Receipts are demos, not proof of payment or tax documents.

The scenario starts on 4 October 2026 for repeatable demonstrations. Settings include a prototype reset.

## Vercel

Deploy the repository as a static site using the Other preset, with no build command and the repository root as the output directory.

## Validation

The source model passed 13 checks for amounts, settlement, duplicates, partial/pending payments, recurrence, reminders and storage. Browser walkthroughs verified the mobile home → Hub → payment → receipt → updated plan → Spend Summary loop.
