# On Balance Volume Scaled - OBV Scaled

## Overview

The main idea of this oscillator is to position the **OBV oscillator** and its oscillation within a range of **0 to approximately -50 to +50**. To achieve this scaling of the *On Balance Volume* oscillator, **Min-max normalization** has been applied.

### Why Scaling Matters?

Since this oscillator does not have a fixed **minimum or maximum**, simply defining max/min values is **not an optimal solution**. Without proper scaling, the following issues arise:
- **Sudden fluctuations** leading to unpredictable volatility.
- **Continuous collisions** with predefined thresholds (+50 & -50), causing frequent bounces and disruptions.

### Solution: Dynamic Normalization

To solve these issues and create **flexible maximum and minimum ranges**, a refined method has been implemented:
- The **maximum** normalization is based on the **moving average of 100 candles** of the OBV index maximum.
- The **minimum** normalization is based on the **moving average of 100 candles** of the OBV index minimum.
- The OBV index is then **normalized using the Min-max method** with these dynamically adjusted ranges.

### Benefits:
- Prevents unwanted **hitting and bouncing** at +50 and -50.
- Ensures **smooth oscillation** while allowing the OBV index to **cross +50 and -50 naturally**.
- Provides **consistent and reliable scaling**, making trend analysis more effective.

## 🔗 Link to the Script
[On Balance Volume Scaled - OBV Scaled](https://www.tradingview.com/script/Z5uXVl3o-On-Balance-Volume-Scaled-OBV-Scaled/)

---

This version is ready for use! Let me know if you need any modifications. 🚀
