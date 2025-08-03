
### Risk Management
- **Risk Per Trade (%)**
- **Reward:Risk Ratio**
- **Max Concurrent Trades**

### Supply & Demand Settings
- **Swing Detection Length**
- **Zone Strength (Tests)**
- **Wick Rejection Sensitivity**
- **Max Zones to Track**

### Liquidity Sweep Settings
- **Lookback Period**
- **Confirmation Bars**
- **Minimum Sweep Distance (%)**

### 🕐 Session Settings
- Enable/disable session filter
- Customize London and NY trading sessions

### 👁️ Visuals
- Toggle zones, sweeps, and previous day levels

---

## Entry Logic

**Long Entry:**
- Bullish liquidity sweep
- Close inside a demand zone
- Price above previous close
- Within allowed session and trade limit
- Confirmed bullish candle

**Short Entry:**
- Bearish liquidity sweep
- Close inside a supply zone
- Price below previous close
- Within allowed session and trade limit
- Confirmed bearish candle

---

## Risk & Position Sizing

Position size is dynamically calculated based on the account equity, chosen risk percentage, and stop-loss distance to ensure consistent risk across trades.

---

## Performance Metrics

At the bottom-right of the chart (if enabled), a table displays:
- Win Rate
- Profit Factor
- Total Trades
- Risk Per Trade
- Open Trades
- Net P&L

---
