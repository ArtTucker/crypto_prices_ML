# Crypto Price ML Analysis
An exploration of various price forecasting algorithms applied to multiple cryptocurrencies.

## Data
We sourced historical crypto price data as CSVs from a Kaggle repository [Cryptocurrency Historical Prices](https://www.kaggle.com/sudalairajkumar/cryptocurrencypricehistory). This data was, in turn, sourced from [CoinMarketCap](https://coinmarketcap.com/). The information recorded in this dataset ran from each currency's initial trading date through the end of Feburary, 2021. It included values for standard market trading data, such as:
- Date : date of observation
- Open : Opening price on the given day
- High : Highest price on the given day
- Low : Lowest price on the given day
- Close : Closing price on the given day
- Volume : Volume of transactions on the given day
- Market Cap : Market capitalization in USD

While this was sufficient for most historical analysis, it did not provide up-to-date market data. For analysis of current data we used Pandas-DataReader to pull data from the Yahoo Finance API. There is a duplicate notebook version of each currency analysis using both data sources.

## Code



## Results