# Commodity Tracker

A single-page dashboard for commodity prices — copper, lithium carbonate, WTI and Brent crude — plus a section for every Excel sheet you import.

**Live page:** https://eye-am-ashutosh.github.io/commodity-dashboard/

## What it does

- Price cards for each commodity with the latest close and day change
- Chart with 1W · 1M · 3M · 6M · YTD · 1Y · 5Y · All, drag-to-zoom, an overview strip and full-screen mode
- Day, Week, Month, YTD and Year % change, calculated by calendar dates or trading sessions, with the formula shown for every value
- Excel-style price table you can copy into Excel or download as CSV
- **Import Excel** (.xlsx, .xls, .csv): each sheet becomes its own section, or is added to an existing one

## Saving data for everyone

Prices you import or add are stored in `data.json` in this repository, so everyone who opens the link sees the same data.

1. Open the live page and import your sheets or add entries — the header shows **Unsaved changes**.
2. Click **Save to GitHub**. The first time, create a fine-grained token with **Contents: Read and write** on this repository only, and paste it in (it stays in your browser).
3. The header changes to **Saved to GitHub** and the data is committed to `data.json`.

Visitors without a token can view and explore everything; their own edits stay in their browser.

## Data sources

- Copper (COMEX), WTI (NYMEX), Brent (ICE): front-month futures daily closes from Yahoo Finance, Sep 2021 – Sep 2026
- Lithium carbonate: owner's spreadsheet and Trading Economics quotes
