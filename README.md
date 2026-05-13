# ERCOT Load Stress Analysis

Exploring ERCOT hourly load dynamics using publicly available grid data and Python.

This project investigates how electricity demand changes across time, how stress events reshape grid behavior, and how volatility emerges across different operational hours.

---

## Project Goals

This analysis explores:

- ERCOT hourly load behavior
- Hour-to-hour load ramps
- Peak demand periods
- Load volatility by hour
- Stress-event vs normal-day comparisons
- Early anomaly detection concepts

The broader goal is to better understand how large-scale human behavior, weather, and operational stress manifest through grid load patterns.

---

## Data Source

- ERCOT Native Load Data
- Public hourly load archives from ERCOT

Future versions will integrate:
- NOAA weather data
- temperature correlation
- humidity and wind analysis
- anomaly classification
- forecasting methods

---

## Tools Used

- Python
- Pandas
- Matplotlib
- Google Colab

---

## Current Analyses

### Average ERCOT Load Shape
Analyzed how demand changes throughout the day and identified typical peak operational hours.

### Hour-to-Hour Load Change
Calculated first-order load differences to study rapid demand ramps and operational transitions.

### Volatility Analysis
Measured standard deviation of load changes by hour to identify periods of elevated instability or uncertainty.

### Stress Day Comparison
Compared Winter Storm Fern load behavior against a normal ERCOT day to observe abnormal system dynamics.

---

## Key Early Observations

- ERCOT load volatility increases substantially during peak operational periods.
- Morning demand ramps occur rapidly between early morning and business-hour transitions.
- Stress-event load shapes differ significantly from normal-day behavior.
- Abnormal weather events create distinct system-wide behavioral signatures visible in load dynamics.

---

## Future Work

Planned next steps include:

- Integrating NOAA weather datasets
- Temperature vs load correlation analysis
- Load forecasting experiments
- Stress-day clustering
- Anomaly detection models
- Network/system visualization techniques
- Exploring decentralized grid behavior and demand response concepts

---

## Why This Project Exists

I’m interested in the intersection of:
- energy systems
- analytics
- network science
- AI-enabled decision support
- risk analysis
- large-scale human behavior

This project is part of a broader effort to better understand how complex systems behave under stress.

---

## Disclaimer

This project is an independent personal learning project using publicly available data sources only.

It is not affiliated with, endorsed by, or representative of my employer or any organization.
