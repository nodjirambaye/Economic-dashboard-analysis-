# 📊 Economic Dashboard Analysis

An advanced Python-based data analysis project for visualizing and forecasting macroeconomic indicators.  
It combines **correlation analysis**, **rolling correlations**, **trend forecasting**, and **recession detection** in one clean dashboard.

---

## 🚀 Features
- **Correlation Heatmap** — Static relationships between Inflation Rate, GDP Growth, and Interest Rate.
- **Rolling Correlation** — Tracks how these relationships change over time.
- **12-Month Forecasting** — Predicts future trends using linear regression (no external heavy libraries).
- **Recession Highlighting** — Shades periods of negative GDP growth.

---

## 📂 Project Structure
```
economic-dashboard/
│
├── economic_dashboard.py       # Main Python script
├── macro_economic_data.csv     # Dataset (sample)
├── README.md                   # This file
├── Economic_Dashboard_Guide.docx # Word project guide
├── correlation_heatmap.png     # Generated heatmap
├── rolling_correlation.png     # Generated rolling correlation plot
└── forecast_with_recession.png # Forecast with recession zones
```

---

## 📸 Screenshots

### Correlation Heatmap
![Correlation Heatmap](correlation_heatmap.png)

### Rolling Correlation
![Rolling Correlation](rolling_correlation.png)

### Forecast with Recession Zones
![Forecast](forecast_with_recession.png)

---

## 📖 Interpretation of Results
1. **Correlation Heatmap**
   - Values near `1.00` = strong positive relationship.
   - Values near `-1.00` = strong negative relationship.
   - Values near `0` = little or no relationship.
   
2. **Rolling Correlation**
   - Shows how relationships shift over time.
   - Example: Inflation and interest rates might be correlated during one period but not in another.

3. **Forecast**
   - Uses historical data to project 12 months ahead.
   - Red dashed lines indicate predicted values.

4. **Recession Zones**
   - Shaded gray areas = negative GDP growth periods.

---

## 🛠 How to Run
1. Download or clone this repository:
   ```bash
   git clone https://github.com/your-username/economic-dashboard.git
   cd economic-dashboard
   ```
2. Make sure Python 3 is installed.
3. Run:
   ```bash
   python economic_dashboard.py
   ```
4. The program will display the visualizations and save them as PNG files.

---

## 📄 License
This project is released under the MIT License — you’re free to use and modify it.

---

## 💡 About
Created as a **portfolio-ready advanced data analysis project** to demonstrate skills in:
- Python Data Analysis
- Visualization with Matplotlib
- Time Series Forecasting
- Economic Insights
