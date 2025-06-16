# Bill Williams NTD Strategy

## Overview

This strategy implements **Bill Williams' NTD method**, combining multiple technical indicators to generate **trade signals**. 

### **Key Indicators Used**
- **Alligator Indicator** (Standard Settings):
  - **Jaw:** Period 13 / Offset 8
  - **Teeth:** Period 8 / Offset 5
  - **Lips:** Period 5 / Offset 3
- **Awesome Oscillator (AO)** – Gauges market momentum.
- **Accelerator Oscillator (AC)** – Helps confirm momentum changes.
- **Fractals** – Identifies key price levels for **stop-loss** points or **breakout confirmations**.

## **Entry Conditions**
### **Long Trade:**
- **Bullish Alligator formation**
- **Positive AO and AC**
- **Closing price above the last detected bear fractal**

### **Short Trade:**
- **Bearish Alligator formation**
- **Negative AO and AC**
- **Closing price below the last bull fractal**

## **Risk Management**
- **Stop-loss:** Set at the **last fractal** (or the **Jaw line** if a fractal is unavailable).
- **Take Profit:** Calculated using a **1:2 risk-to-reward ratio**.

## **Visualization**
All **key indicator lines** and **fractal markers** are plotted directly on the chart for **easy analysis**. 
To display the plotted indicators, **enable 'Enable Plot'** in the input tab of the settings.

---

🔗 Link to the script: [Bill Williams NTD Strategy](https://www.tradingview.com/script/BHmbnqPP-Bill-Williams-NTD-Strategy/)

---

This version is ready to use! Let me know if you need any modifications. 🚀
