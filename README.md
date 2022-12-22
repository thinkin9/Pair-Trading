# Pair-Trading

## Files
1. pair_trading.ipynb: Do pair-trading with jupyter notebook
2. examples.md (Not yet)

## pair_trading.ipynb
### Contents
1. (Prepare) pip install & library
2. (Input) Ticker & Exchange
3. (Load) Load a price data via FinanceDataReader
4. (Pre-process) Unify a unit of currency
5. (Pre-process) Remove redundant "nan" rows
6. (Calculate) Calculate spreads and error rates of spread
7. Result
8. Reference

### What you do? Set Three!
1. Set tickers
2. Set exchanges (NYSE, NASDAQ, AMEX, OTC, EURONEXT, XETR, KRX, TSE, SZSE, SSE, HKEX)
3. Set period

### What you get? Get Three!
1. Price Chart with each currencies
2. Price Chart with unified currency
3. Coefficient and Log-Spread Chart   
![image](https://user-images.githubusercontent.com/53069520/209064172-b495e798-8a01-4caa-9c01-ec8734eeb731.png)   
![image](https://user-images.githubusercontent.com/53069520/209064211-2cd7dcba-3ec5-439f-a649-473aa7c84266.png)   
COEF_correlation:  0.970381   
COEF_cointegration:  0.714987   
STD_err:  0.113124   
![image](https://user-images.githubusercontent.com/53069520/209064321-e73d0f71-6f7c-4c7e-ada0-ef562d833836.png)
