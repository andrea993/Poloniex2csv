# poloniex2csv
This scirpt read historic data from [Poloniex](https://poloniex.com/) API and make a csv of three columns (`[TIMESTAMP],[VALUE],[VOLUME]`) in order to import cryptocurrencies charts in any program that supports csv file.

## Usage
```
poloniex2csv [pair] 
```

## Example
```
./poloniex2csv USDT_BTC
Download data...
Parse data...
Write USDT_BTC.csv...
```
