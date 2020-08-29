# Top-10-Market-Capitalization-Index
Scraping market data for top 10 market capitalization index construction.

This paper presents the construction of a time series of index values starting with 1.0, which represents the performance of a portfolio that is fully rebalanced at the beginning of the time series and then at the beginning of each month, and includes the top 10 companies by market capitalization at the date of rebalancing. The weights in this portfolio at the rebalancing date are set in proportion to the previous month's stock returns. If a stock shows a negative return, then the position on it is short.

**Historical_data_from_Yahoo.ipynb** - [original code](https://github.com/Gunjan933/stock-market-scraper)

**Market_cap_data from_Ycharts.ipynb** - scraping data from Ycharts.com. You must register on the site Ycharts.com and enter the credentials in the variables 'login' and 'password'

**Analisys.ipynb** - analisys and construction index from data. Only part of the downloaded data was taken into account in the results of this example

[Tickers file link](http://investexcel.net/wp-content/uploads/2015/01/Yahoo-Ticker-Symbols-September-2017.zip)
