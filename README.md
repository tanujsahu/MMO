# MMO
Math Metical Operation

A simple package for basic mathematical operations (addition, subtraction, multiplication).

## Installation

You can install this package using npm:

```sh
npm install @tanuj_sahu_ts/mmo

# USAGE 

import { add, subtract, multiply } from '@tanuj_sahu_ts/mmo';

// Basic operations
console.log(add(2, 3));        // 5
console.log(subtract(5, 2));   // 3
console.log(multiply(3, 4));   // 12

// Using variables
const a = 10;
const b = 20;

console.log(`The sum of ${a} and ${b} is ${add(a, b)}`);            // The sum of 10 and 20 is 30
console.log(`The difference between ${a} and ${b} is ${subtract(a, b)}`); // The difference between 10 and 20 is -10
console.log(`The product of ${a} and ${b} is ${multiply(a, b)}`);    // The product of 10 and 20 is 200

// In functions
function calculateOperations(x, y) {
  return {
    addition: add(x, y),
    subtraction: subtract(x, y),
    multiplication: multiply(x, y)
  };
}

const results = calculateOperations(7, 3);
console.log(results); // { addition: 10, subtraction: 4, multiplication: 21 }

