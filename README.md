# Premium-Advanced-Indicator
Premium Advanced Indicator -  OZV Oscillator Zone Volume

# Volume Zone Oscillator (OZV) Indicator

## 📖 Overview
The **Volume Zone Oscillator (OZV)** is a technical indicator that analyzes volume changes in relation to predefined levels (zones) while incorporating price data. Unlike traditional volume oscillators, the OZV combines price and volume to provide deeper insights into market trends and momentum.

This repository provides the Python implementation of the OZV indicator, complete with visualization and signals for trend analysis.

---

## 📊 What is the Volume Zone Oscillator?

### Definition
The OZV is calculated as the percentage ratio of:
1. **Price-related EMA of Volume**: Volume is positive if the current bar's close is higher than the previous bar, and negative otherwise. This is similar to On-Balance Volume (OBV).
2. **General EMA of Volume**: A simple exponential moving average of volume.

The resulting ratio is plotted and analyzed using predefined levels.

### Key Levels
- **+60**, **+40**, **+15**, **-5**, **-40**, **-60**
These levels define different zones for buy and sell signals based on the OZV line.

### Confirmation Indicators
To validate trends and improve signal accuracy, the following indicators are used:
1. **60-period EMA**: Determines trend direction.
   - Price above the EMA indicates an uptrend.
   - Price below the EMA indicates a downtrend.
2. **14-period ADX**: Confirms trend existence.
   - **ADX > 18**: Trending market.
   - **ADX ≤ 18**: Non-trending market.

Using these indicators, you can identify actionable buy/sell signals when the OZV crosses key levels.

---

## 🚀 Features
- **OZV Calculation**: Computes the ratio of price-related EMA of volume to general EMA of volume.
- **Signal Zones**: Highlights critical levels for buy and sell signals.
- **Trend Validation**:
  - **60-period EMA** for trend direction.
  - **14-period ADX** for trend confirmation.
- **Chart Visualization**: Displays the OZV plot with colored zones and optional trend arrows.

---

