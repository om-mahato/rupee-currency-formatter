# Rupee Currency Formatter
This package transforms given string or number into into Indian Currency Format (INR)
with default rupee symbol (₹) or any custom symbol and with specified decimal places.

## Installation
```
npm install indian-currency-formatter
```

## Usage
```
import indianCurrancyFormat from 'indian-currency-formatter';

or

const indianCurrancyFormat = require('indian-currency-formatter');
```

## Examples
```
console.log(indianCurrancyFormat(9876.54, 'INR', 3)); // INR 9,876.540
console.log(indianCurrancyFormat(9876543.21)); // ₹ 9,876,543.21
```