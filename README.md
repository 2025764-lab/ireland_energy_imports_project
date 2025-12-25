 Ireland Energy Imports — CA2 Project

This project analyses Ireland’s energy import dependency using data from:

- Eurostat
- SEAI (Sustainable Energy Authority of Ireland)
- World Bank

The project contains:
- Notebook 1: Data cleaning, EDA, and inferential statistics
- Notebook 2: Forecasting (ARIMA) and clustering (K-means)
- Notebook 3: Dashboard figures generation
- Figures stored in `/figures`
- Cleaned data stored in `/data/processed`

The analysis follows:
- Tufts Visualization Principles
- Good statistical practice
- Clear, reproducible workflows

This repository is the submission for Continuous Assessment 2 (CA2) for MSc Data Analytics.


## How to Run

Activate the Conda environment and run the notebooks in order:

1. `notebooks/01_data_eda_stats.ipynb`
2. `notebooks/02_ml_forecasting_clustering.ipynb`
3. `notebooks/03_dashboard.ipynb`

## Dashboard Note

The dashboard in Notebook 3 uses ipywidgets.
Interactive widgets do not render in GitHub preview and must be run locally.
