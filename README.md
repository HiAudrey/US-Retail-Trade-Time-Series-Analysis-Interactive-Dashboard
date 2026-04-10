# US Retail Trade — Time Series Analysis & Interactive Dashboard

An interactive R Shiny application for analyzing and forecasting 30 years of US monthly retail trade data (Jan 1992 – Jan 2023).

**[→ Launch the Live App]([https://hiaudrey.shinyapps.io/shinyapp/])**

---

## What This Does

- Analyzes 30+ years of US Census retail trade data to surface seasonal patterns, long-term trends, and structural shifts
- Forecasts future retail activity using HoltWinters exponential smoothing
- Delivers findings through an interactive Shiny dashboard where users can filter, explore, and compare across time periods

---

## Technical Approach

**Data Pipeline**
- Raw data sourced from [US Census Monthly Retail Trade](https://www.census.gov/retail/mrts/www/mrtssales92-present.xlsx)
- Cleaned, transformed, and structured for time series analysis in R

**Modeling**
- Time series decomposition (trend, seasonal, residual)
- HoltWinters exponential smoothing for forecasting
- Model evaluation with residual diagnostics

**Visualization & App**
- Built with R Shiny for interactive exploration
- Dynamic filtering, real-time chart updates, and user-controlled parameters
- Designed for non-technical stakeholders to explore data independently

---

## Tech Stack

R · R Shiny · ggplot2 · HoltWinters · Time Series Analysis

---

## Project Structure

```
├── shinyApp/          # Shiny application (ui.R + server.R)
├── slides/            # Presentation deck
├── READGUIDE.md       # Detailed methodology
└── README.md
```

---

## Key Takeaway

This project demonstrates end-to-end data analysis: from raw government data → statistical modeling → interactive product that a business user can explore without writing code.
