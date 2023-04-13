# Rupee Currency Formatter
This package transforms given string or number into into Indian Currency Format (INR)
with default rupee symbol (₹) or any custom symbol and with specified decimal places.

## Installation
```
npm install rupee-currency-formatter
```

## Usage
```
import rupeeCurrencyFormatter from 'rupee-currency-formatter';

or

const rupeeCurrencyFormatter = require('rupee-currency-formatter');
```

## Examples
```
console.log(rupeeCurrencyFormatter(9876.54, 'INR', 3)); // INR 9,876.540
console.log(rupeeCurrencyFormatter(9876543.21)); // ₹ 9,876,543.21
```