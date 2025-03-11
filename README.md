# Credit Card Checker

This project contains functions to validate credit card numbers using the Luhn algorithm, find invalid credit card numbers, and identify the companies that issued these invalid numbers.

## Functions

1. **validateCred(arr)**: 
   - Takes an array of digits representing a credit card number.
   - Returns `true` if the number is valid, `false` otherwise.

2. **findInvalidCards(cards)**: 
   - Takes a nested array of credit card numbers.
   - Returns a nested array of invalid credit card numbers.

3. **idInvalidCardCompanies(invalidBatch)**: 
   - Takes a nested array of invalid credit card numbers.
   - Returns an array of companies that issued these invalid numbers.

## Usage

To use these functions, simply call them with the appropriate arguments. For example:

```javascript
console.log(validateCred(valid1)); // true or false
console.log(findInvalidCards(batch)); // Array of invalid card numbers
console.log(idInvalidCardCompanies(findInvalidCards(batch))); // Array of companies