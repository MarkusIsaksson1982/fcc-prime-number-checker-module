# Prime Number Checker Module

This is my submission for the freeCodeCamp lab [Build a Prime Number Checker Module](https://www.freecodecamp.org/learn/back-end-development-and-apis-v9/lab-prime-number-checker-module/lab-prime-number-checker-module), part of Back End Development and APIs.

`index.js` defines `isPrime(num)`, which returns `true` for prime numbers and `false` otherwise (including for 0, 1, negative numbers, decimals and non-numbers). It is exported as a named property of `module.exports`.

```js
const { isPrime } = require('./index.js');

isPrime(7);  // true
isPrime(9);  // false
```
