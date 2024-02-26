# Crypto Price Converter

A simple npm module to convert cryptocurrency prices between different currencies.

## Installation

You can install the module via npm:

```bash
npm install crypto-price-converter
```

## USAGE

```javascript
const convertCryptoCurrencyPrice = require('crypto-price-converter');

convertCryptoCurrencyPrice('BTC', 'USD')
  .then(price => console.log(`1 BTC is currently worth $${price} USD`))
  .catch(err => console.error('Error:', err.message));
```