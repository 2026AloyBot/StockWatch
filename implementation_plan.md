# StockWatch Implementation Plan

## Top 5 Features (Research Summary)

Based on common retail investor needs:

1. **Portfolio Summary Dashboard** - Total value, daily P&L, overall gain/loss at a glance
2. **Dividend Tracking** - Expected dividends, yield, payment dates
3. **Price Alerts** - Notifications when price hits target (above/below)
4. **Multiple Portfolios** - Group stocks into different portfolios (e.g., "Growth", "Retirement")
5. **Cost Basis Tracking** - Average cost, total invested, tax implications

---

## Implementation Checklist

### ☐ Feature 1: Portfolio Summary Dashboard
- [ ] Add header showing total portfolio value
- [ ] Show total daily change ($ and %)
- [ ] Show total gain/loss since purchase
- [ ] Display number of stocks being tracked

### ☐ Feature 2: Dividend Tracking
- [ ] Add dividend yield field to stock data
- [ ] Show annual dividend estimate
- [ ] Display dividend frequency (quarterly, annually)

### ☐ Feature 3: Price Alerts (Enhanced)
- [ ] Add "Alert me when price is ABOVE $X"
- [ ] Add "Alert me when price is BELOW $X" 
- [ ] Show active alerts on each stock card
- [ ] Visual indicator when alert triggers

### ☐ Feature 4: Multiple Portfolios
- [ ] Add "Create Portfolio" button
- [ ] Allow naming portfolios (e.g., "Growth", "Retirement")
- [ ] Add stock to specific portfolio
- [ ] Filter view by portfolio

### ☐ Feature 5: Cost Basis & Tax Info
- [ ] Calculate total invested amount
- [ ] Show average cost per share
- [ ] Display unrealized gain/loss in $
- [ ] Show capital gains (if sold concept)

---

## Notes
- All data stored in localStorage (or Firebase when configured)
- Test each feature before moving to next
- Prioritize mobile-friendly interactions
