# 🏆 Tourism-Driven Housing Pressure Analysis
### TSA State Finalist Project

A data science research project investigating the relationship between short-term rental platforms (e.g., Airbnb) and housing affordability in New York City using publicly available datasets, statistical modeling, and data visualization.

The project integrates housing market data, census statistics, and Airbnb listing information to quantify housing pressure across NYC boroughs through regression analysis and a custom Housing Pressure Index (HPI).

---

## Overview

This project explores how the growth of short-term rentals influences rental prices, home values, and housing affordability.

Using Python and several public datasets, the analysis produces publication-quality visualizations, performs statistical regression, and introduces a custom composite metric that measures tourism-driven housing pressure.

The project was developed for the **Technology Student Association (TSA) Data Science Competition**, where it was recognized as a **State Finalist**.

---

## Features

- Analysis of Airbnb listing density across NYC boroughs
- Housing affordability trend analysis (2015–2024)
- Rent and home value growth visualization
- Linear regression modeling
- Pearson correlation analysis
- Custom Housing Pressure Index (HPI)
- Executive summary dashboard
- Eight publication-quality figures generated automatically
- Fully reproducible workflow

---

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- SciPy
- Scikit-learn

---

## Data Sources

The analysis combines several publicly available datasets, including:

- Inside Airbnb (NYC 2024)
- Zillow Observed Rent Index (ZORI)
- Zillow Home Value Index (ZHVI)
- U.S. Census Bureau ACS 5-Year Estimates
- Peer-reviewed literature from *Marketing Science* and *Environment & Planning A*

All datasets and academic references are cited within the project.

---

## Methodology

The project follows a reproducible data science workflow:

1. Load publicly available housing and demographic datasets.
2. Clean and standardize the data.
3. Analyze borough-level housing trends.
4. Compute descriptive statistics.
5. Perform linear regression and correlation analysis.
6. Construct a custom Housing Pressure Index (HPI) that combines:
   - Short-term rental density
   - Rent growth
   - Median household income
7. Generate publication-quality visualizations.
8. Produce an executive summary dashboard.

---

## Housing Pressure Index (HPI)

The Housing Pressure Index is a composite metric designed to estimate the relative impact of short-term rentals on housing affordability.

The index incorporates:

- Active Airbnb listings per 1,000 residents
- Rent growth
- Median household income (normalized against the national median)

Scores are normalized to a 0–100 scale to facilitate comparison between boroughs.

---

## Figures Generated

Running the script automatically generates eight figures, including:

- Airbnb listing distribution
- Rent vs. income growth
- Home value vs. income growth
- STR density vs. rent burden
- Housing Pressure Index rankings
- OLS regression analysis
- Commercial operator analysis
- Executive summary dashboard

All figures are saved to the `figures/` directory.

---

## Installation

```bash
pip install -r requirements.txt
```

---

## Running

```bash
python tourism_housing_pressure.py
```

The program automatically:

- Loads all datasets
- Performs statistical analysis
- Generates all figures
- Saves visualizations as PNG files
- Prints summary tables and citations

---

## Repository Structure

```
.
├── tourism_housing_pressure.py
├── requirements.txt
├── figures/
├── README.md
```

---

## Concepts Demonstrated

- Data Science
- Statistical Analysis
- Regression Modeling
- Data Visualization
- Feature Engineering
- Composite Index Design
- Housing Economics
- Reproducible Research
- Python Scientific Computing

---

## Future Improvements

Potential extensions include:

- Zip code–level analysis
- Interactive dashboard using Plotly or Dash
- Machine learning models for housing price prediction
- Time-series forecasting
- Geospatial visualization with GeoPandas
- Automated data updates from public APIs

---

## Recognition

🏆 **Technology Student Association (TSA) — Data Science Competition**

**State Finalist**

---

## License

This repository is intended for educational and research purposes.
