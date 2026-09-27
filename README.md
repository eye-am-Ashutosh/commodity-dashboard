# Commodity Tracker

A single-page dashboard for commodity prices — copper, lithium carbonate, WTI and Brent crude — plus a section for every Excel sheet you import.

**Live page:** https://YOUR-USERNAME.github.io/commodity-tracker/

## What it does

- Price cards for each commodity with the latest close and day change
- Chart with 1W · 1M · 3M · 6M · YTD · 1Y · 5Y · All, drag-to-zoom, an overview strip and full-screen mode
- Day, Week, Month, YTD and Year % change, calculated by calendar dates or trading sessions, with the formula shown for every value
- Excel-style price table you can copy into Excel or download as CSV
- **Import Excel** (.xlsx, .xls, .csv): each sheet becomes its own section, or is added to an existing one

## Updating the published data

1. Open the live page, import your sheets or add entries.
2. Click **Save dashboard file** — it downloads a copy with your data inside.
3. Rename that file to `index.html`, upload it here (**Add file → Upload files**) and commit.

Changes made by visitors are saved only in their own browser; the published page changes only when a new `index.html` is uploaded.

## Data sources

- Copper (COMEX), WTI (NYMEX), Brent (ICE): front-month futures daily closes from Yahoo Finance, Sep 2021 – Sep 2026
- Lithium carbonate: owner's spreadsheet and Trading Economics quotes
