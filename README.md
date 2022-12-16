# Simple ARIMA Models for Forecasting Stock Prices

This repository contains a Jupyter notebook file that demonstrates how to use ARIMA models for forecasting stock prices. The notebook uses the auto_arima function from the pmdarima library to automatically select the best ARIMA model for the given data, but also allows users to manually specify the model parameters using the ARIMA class from the statsmodels library. The notebook also includes examples of how to use the acf and pacf functions from statsmodels to perform Autocorrelation Function (ACF) and Partial Autocorrelation Function (PACF) tests on the data. The result is at the very end of the notebook.

## Requirements
In order to use the Jupyter notebook in this repository, you will need to have the following installed:

- Python 3.9.3 or later
- Jupyter Notebook
- The pandas, numpy, pmdarima, statsmodels, and matplotlib libraries

## Usage
To use the Jupyter notebook in this repository, follow these steps:

1. Clone or download the repository to your local machine.
2. Open a command prompt or terminal and navigate to the directory containing the repository.
3. Run the command jupyter notebook to start the Jupyter notebook server.
4. In your web browser, navigate to http://localhost:8888 to open the Jupyter notebook interface.
5. Click on the stock_forecast.ipynb file to open the notebook.
6. Follow the instructions in the notebook to fit and forecast ARIMA models for stock prices.

## License
This respository is licensed under Apache-2.0 license. 