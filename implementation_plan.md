# StockWatch Implementation Plan

## Top 5 Features (Research Summary)

Based on common retail investor needs:

1. **Portfolio Total value, daily Summary Dashboard** - P&L, overall gain/loss at a glance
2. **Dividend Tracking** - Expected dividends, yield, payment dates
3. **Price Alerts** - Notifications when price hits target (above/below)
4. **Multiple Portfolios** - Group stocks into different portfolios (e.g., "Growth", "Retirement")
5. **Cost Basis Tracking** - Average cost, total invested, tax implications

---

## Implementation Checklist

### ☑ Feature 1: Portfolio Summary Dashboard
- [x] Add header showing total portfolio value
- [x] Show total daily change ($ and %)
- [x] Show total gain/loss since purchase
- [x] Display number of stocks being tracked

### ☑ Feature 2: Dividend Tracking
- [x] Add dividend yield field to stock data
- [x] Show annual dividend estimate
- [x] Display dividend frequency (quarterly, annually)

### ☑ Feature 3: Price Alerts (Enhanced)
- [x] Add "Alert me when price is ABOVE $X"
- [x] Add "Alert me when price is BELOW $X" 
- [x] Show active alerts on each stock card
- [x] Visual indicator when alert triggers

### ☑ Feature 4: Multiple Portfolios
- [x] Add "Create Portfolio" button
- [x] Allow naming portfolios (e.g., "Growth", "Retirement")
- [x] Add stock to specific portfolio
- [x] Filter view by portfolio

### ☑ Feature 5: Cost Basis & Tax Info
- [x] Calculate total invested amount
- [x] Show average cost per share
- [x] Display unrealized gain/loss in $
- [x] Show annual dividend income

---

## Notes
- All data stored in localStorage (or Firebase when configured)
- Test each feature before moving to next
- Prioritize mobile-friendly interactions
