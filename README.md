# Sticker Sales Forecasting and Analysis

This repository contains the data and code for analyzing and forecasting sticker sales using exploratory data analysis (EDA) and time-series modeling. 

## Project Structure

- **`data/`**: Contains all the data files used in the analysis.
- **`Forecasting_Sticker_Sales_EDA.ipynb`**: Jupyter notebook for exploratory data analysis of sticker sales, including preprocessing, aggregation, and initial visualizations.
- **`Forecasting_Sticker_Sales_Time_Series.ipynb`**: Jupyter notebook for time-series modeling, including ARIMA model implementation and forecasting sticker sales.

## Getting Started

To run the code in this repository, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/sticker-sales-forecasting.git
   cd sticker-sales-forecasting


## Notebooks Overview

### `Forecasting_Sticker_Sales_EDA.ipynb`
This notebook focuses on:
- Data loading and cleaning.
- Aggregation by country, store, product, and date.
- Creating new features such as `product_country`, `product_store`, and `country_store`.
- Initial visualizations to understand data trends.

### `Forecasting_Sticker_Sales_Time_Series.ipynb`
This notebook focuses on:
- Time-series preprocessing and stationarity checks using the Augmented Dickey-Fuller (ADF) test.
- Fitting ARIMA models to forecast sticker sales.
- Model evaluation using MAPE and visualizations of forecast results.

## Data
The data used for this analysis is stored in the `data/` folder. Ensure all data files are placed in this directory before running the notebooks.

## Requirements
The code was developed using the following Python libraries:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `statsmodels`
- `pmdarima`
- `scikit-learn`
- `jupyterlab`

To install all dependencies, use the `requirements.txt` file provided.

## Results
The results include:
- Insights into sticker sales trends across countries, stores, and products.
- Forecasts for sticker sales using ARIMA models, evaluated using MAPE.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Acknowledgments
- Kaggle for providing the initial dataset.
- Python libraries like `statsmodels` and `pmdarima` for time-series modeling.
