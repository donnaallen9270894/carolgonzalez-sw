# Carolgonzalez-sw

Carolgonzalez-sw is a Node.js module containing a collection of magical tools for developers.

## Installation

You can install Carolgonzalez-sw via npm: `npm install carolgonzalez-sw`

## Usage

```javascript
const magic = require('magic-tools');

// Generate a random string
const randomString = magic.generateRandomString(10);
console.log('Random String:', randomString);

// Check if a number is prime
const isPrime = magic.isPrime(17);
console.log('Is Prime:', isPrime);

// Fetch data from a URL
magic.fetchData('https://api.example.com/data')
  .then(data => console.log('Fetched Data:', data))
  .catch(error => console.error('Error:', error.message));
```