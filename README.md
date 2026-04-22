# Mitescu Household Finance App

Personal finance dashboard for Razvan & Paula Mitescu.

## Setup

1. Go to **Settings** (bottom left) and paste your Anthropic API key
2. Get a key at https://console.anthropic.com → API Keys → Create Key
3. Set a billing limit of $10/month (you'll use ~$1-2/month)

## Monthly workflow

1. Click **Upload Statements** in the sidebar
2. Select the month
3. Upload PDFs or screenshots for each bank:
   - CGD (main PT account)
   - ActivoBank (loan + Visa CC)
   - Revolut
   - ING RO Current, Savings, Credit Card
   - Unicredit (mortgage screenshots)
   - CGD Gold Card
4. Click **Analyze with AI** — Claude reads all statements and categorizes
5. Dashboard updates automatically

## Hosting on GitHub Pages

1. Create repo `finance-app` on github.com/razvanm-tech
2. Upload `index.html` to the repo
3. Go to Settings → Pages → Source: main branch → Save
4. App live at: https://razvanm-tech.github.io/finance-app/

## Pre-loaded data

- All merchant mappings from 6 months of verified statements
- Paula's fixed RO costs (€752/mo) auto-included
- Budget targets per category with traffic light alerts
- RSU schedule, debt tracker, 2026 plan
