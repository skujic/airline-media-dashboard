# Wizz Air Media Intelligence Web App

Open `index.html` in any modern browser.

## What it does
- Shows your current Wizz Air UK dataset
- Lets you upload additional CSV exports from Apify
- Supports multi-company analysis for Wizz Air UK and competitors
- Includes a Daily Feed view for the last 24 hours of loaded data

## Expected CSV columns
The app works best with Apify exports containing:
- title
- url
- source
- publishedAt
- description
- language
- country

Optional:
- company

If `company` is missing, the app will ask you which airline the uploaded CSV belongs to.

## Best daily workflow
1. In Apify, save one task per airline and country pair.
2. Schedule each task to run daily.
3. Export results to CSV or fetch dataset items via the API.
4. Drag the CSVs into this app to refresh the dashboard.

## Primary competitors preloaded in the app config
- Wizz Air UK
- Wizz Air
- Ryanair
- easyJet
- British Airways
- Jet2
- TUI Airways
- Loganair
