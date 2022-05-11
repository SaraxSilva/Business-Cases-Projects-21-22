# BC4: Cryptocurrency Value Prediction

**Problem type:** Forecasting

**Submission date:** 09-05-2022 | 11.59pm

## General Context

Forecasting is a technique used to predict future events based on historical
data. The quality of these predictions can then be compared to what actually
happens. For example, sports and politics betting is a form of forecasting. In
this scenario, bettors are paid based on the outcome of their predictions. In
its statistical sense, forecasting approaches typically use time series,
cross-sectional, or longitudinal data. 

## Business Situation

Cryptocurrencies are essentially digital currencies that allow individuals to
transact online without the use of traditional financial institutions. The
surge in cryptocurrency value and popularity has raised concerns of
speculation. But its true application in the real world is still unproven,
even for those creating and trading cryptocurrencies.

Just like many other financial assets, the value of cryptocurrencies is
particularly volatile and is only worth what someone will pay for it. During
the past year, cryptocurrencies lost a significant portion of their value as
more regulations are enacted globally. Cryptocurrencies like Bitcoin and Ether
became popular because of the lack of regulations on cryptocurrencies in
comparison to other financial assets. In particular, financial institutions
cannot charge prohibitive fees to transfer funds with cryptocurrencies like a
bank can with its traditional payment systems.

Investing in cryptocurrencies can be an exciting new area of finance for many
risk-loving investors. In addition to the risks associated with unregulated
markets and the lack of regulations that come with this type of investing,
investing in cryptocurrencies is particularly challenging, regardless of the
knowledge or experience an investor has. Although many individuals understand
what Bitcoin, Ether and other cryptocurrencies are, few have the skills to do
proper data-driven trading.

Investments4Some is a long-standing Portuguese, privately-held hedge funds
management firm. They use traditional statistical methods and financial
indicators to measure the quality of their portfolios. A few years ago, the
company begun to explore the usage of Machine Learning models for market price
forecasting, but given the lack of maturity of the company in Machine
Learning, their newly created department is failing to successfully develop
these models and bring them into production.

Investments4Some is aware of the lack of sophistication of the average
investor, and is well aware of the potential of Machine Learning methods to
anticipate market trends and increase the expected returns of their
investments. They know that with a good enough forecasting model, they could
more accurately predict market prices and anticipate trends. As such, Warner
Buffer and Gil Bates, partners of Investments4Some, have asked you to build
them a forecasting model in order to predict the daily value of
cryptocurrencies. To do this, you have been provided a dataset containing the
daily prices of 10 cryptocurrencies. 

## Metadata

All cryptocurrencies found in the dataset are valued in terms of USD. For
example, a value of 400 USD means a unit of a cryptocurrency is worth that much
in American dollars. The symbols presented below are shown as represented in
Yahoo! Finance. Cryptocurrencies present in the dataset:

- ADA-USD: Cardano
- ATOM-USD: Cosmos
- AVAX-USD: Avalanche
- AXS-USD: Axie Infinity
- BTC-USD: Bitcoin 
- ETH-USD: Ethereum 
- LINK-USD: Chainlink 
- LUNA1-USD: Terra 
- MATIC-USD: Polygon 
- SOL-USD: Solana 

For each of these cryptocurrencies the following data is present in the
different csv files:

- Low: Lowest price during a day
- High: Highest price during a day
- Open: Price at the start of the day
- Close: Price at the end of the day
- Adj. Close: Closing price after adjustments for all applicable splits and
  dividend distributions. Data is adjusted using appropriate split and
  dividend multipliers, adhering to Center for Research in Security Prices
  (CRSP) standards.
- Volume: Amount of an asset or security that changes hands over the course of
  a day


## Expected outcomes

1. Explore the data and build models to answer the problem:
    - Build a predictive model to predict as accurately as possible future stock
      prices.
    - If necessary, collect external sources of data that might help your
      model's performance.

> **WARNING:** You may not use data referring to date periods after the
> presentation of this business case (April 26th, 2022). Anything before that
> is fine.

2. Two days before the presentation (Sunday, May 8th):
    - An updated set of CSV files with the same format as the ones provided
      originally will be uploaded here by the end of the day. 
    - You are expected to use this updated data to retrieve your model's
      predictions for the cryptocurrencies listed above for the closing time
      of May 10th.
    - You should send your predictions via e-mail with the subject "BCwDS
      21/22 - BC4 - Group ## - Crypto value prediction" to the course
      instructors in the following format (no other e-mail content is
      necessary):
      ```
      - ADA-USD: ####
      - ATOM-USD: ####
      ...
      - SOL-USD: ####
      ```

3. At the day of the presentation, you are expected to: 
    - Present the work you did, the expected performance of the model,
      benchmarks and all other approaches tested.
    - Present your model's predicted prices for the days of the presentations,
      along with a general analysis with key takeaways from these predictions
      (assuming no knowledge of the market prices at the time of the
      presentation).

> **NOTE:** You may use any tool, library, programming language or secondary
> sources of data you may find relevant.

## Useful resources

- [10 Trading Indicators Every Trader Should Know](https://www.ig.com/en/trading-strategies/10-trading-indicators-every-trader-should-know-190604)
- [Top 4 Python Libraries for Technical Analysis](https://medium.com/geekculture/top-4-python-libraries-for-technical-analysis-db4f1ea87e09)
- [Top 7 Technical Analysis Tools](https://www.investopedia.com/top-7-technical-analysis-tools-4773275)
