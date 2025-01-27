# Seasonal Forecast Verification

This repository contains analysis for verifying and assessing seasonal forecast accuracy and skill. It is designed for researchers and practitioners working with climate forecasts, enabling evaluation and visualization of probabilistic forecast performance.

## Features

- **Skill Metrics**: Evaluate forecasts using common metrics like:
  - Correlation (e.g., Pearson, Spearman)
  - Continuous Ranked Probability Skill Score (CRPSS)
- **Visualization**: 
  - Time series comparisons
  - Scatter plots
  - Heatmap of skill 
- **Flexible Analysis**: Customizable for various datasets, regions, variables, and temporal scales.
- **Support for Observations**: Integrate observational or reanalysis data for benchmarking.

## Explanation
- **data**: contains the original NetCDF data use in the analysis
- **download**: contains the python scripts to download the data from Copernicus CDS API service
- **verification.ipynb**: contains the analysis

## Installation

Clone the repository to your local machine:

```bash
git clone https://github.com/danielmerbet/seasonal_forecast_verification.git
cd seasonal_forecast_verification
