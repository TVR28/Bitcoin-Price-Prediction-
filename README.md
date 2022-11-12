# Bitcoin-Price-Prediction-
## Predicting Bitcoin Price Using Historical Data And Wikipedia Edits Data 

In this project, we'll predict the future price of Bitcoin.  We'll use historical data of the price of Bitcoin, along with data from Wikipedia about edits to the Bitcoin page.  We'll merge and combine this data, then use it to train a `Random Forest` model which tells us if Bitcoin prices will increase or decrease tomorrow.  We'll then switch to an `XGBoost` model and better predictors to improve accuracy.

We'll develop a backtesting system and use a robust error metric so we can tell if the algorithm is performing well.

This project can be extended to other cryptocurrencies as well like etherium (ETH).

## Code

You can find the code for this project [here](https://github.com/TVR28/Bitcoin-Price-Prediction-/blob/main/Bitcoin%20Price%20Prediction.ipynb)

## Data

Computing the Wikipedia edit data takes time.  It can be faster to use the version that's already been generated.  It's in this repository, and called `wikipedia_edits.csv`.

We'll be downloading the Bitcoin price data using the `yfinance` package as part of the project.

