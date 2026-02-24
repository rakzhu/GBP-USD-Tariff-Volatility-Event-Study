# GBP-USD-Tariff-Volatility-Event-Study

##  Overview
This project examines the impact of the 2025 US tariff announcements on GBP/USD volatility using an event-study framework with GARCH(1,1) models. GBP/EUR serves as a control to isolate UK-specific effects.

## Tools & Libraries
- Python: pandas, numpy, matplotlib, seaborn, statsmodels, arch
- R: rugarch (for extended GARCH modelling)
- Excel: Data cleaning & preparation

## Methodology
1. **Data Preparation**: Daily exchange rates for GBP/USD and GBP/EUR, log returns calculated.
2. **Descriptive Analysis**: Mean, standard deviation, min/max, percentiles.
3. **Correlation Analysis**: GBP/USD vs GBP/EUR to test spillovers.
4. **GARCH(1,1) Modeling**: Captures volatility clustering and shock persistence.
5. **Conditional Volatility Plotting**: Visualizes periods of high FX risk.
6. **Event Dummies**: Created for tariff imposition ("bad news") and relief events ("good news").
7. **Robustness Checks**: Different event windows, overlapping macro events, alternative volatility measures.

## Key Findings
- Bad news (tariff impositions) caused strong volatility spikes in GBP/USD.
- Good news (tariff relief) had limited effect.
- GBP/EUR control confirms these effects are UK-specific.
- Supports event-driven volatility modeling for policy shocks.

