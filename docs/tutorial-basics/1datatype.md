---
sidebar_position: 1
---

# DataTypes

📋 List of available data types in javascript:

1. 💬 **String**: Represents sequences of characters, enclosed in single or double quotes.
2. 🔢 **Number**: Represents both integer and floating-point numbers.
3. 🔍 **BigInt**: Represents arbitrary precision integers (introduced in ES11/ES2020).
4. 🧮 **Boolean**: Represents binary values, either true or false.
5. 🚫 **Undefined**: Represents a variable that has been declared but hasn't been assigned a value.
6. 📭 **Null**: Represents the intentional absence of any value or object.
7. 🔑 **Symbol**: Represents unique and immutable values, often used as object property keys.
8. 📦 **Object**: Represents collections of key-value pairs, properties, and methods.

🧱 These data types provide the foundational building blocks for working with data and values in JavaScript.


## DataTypes

Variable are just like container that hold the data:

```js title="Declaration of Variables"

// Numbers:
let length = 20;
let weight = 71.5;

// Strings:
let color = "Green";
let firstName = "Ryan";

// Booleans
let x = true;
let y = false;

// Object:
const person = {firstName:"Tom", lastName:"Hardy"};

// Array object:
const colors = ["Green", "White", "Blue"];

// Date object:
const date = new Date("2020-03-25");
```

### Numbers
There are two major types of number in js they are
1. Integers : These are the whole number without any decimal point
2. Floating : These consist of decimals

```
const integer = 10;
const floatingNumber = 8.2.;
integer;
floatingNumber;
```

### Mathematical Operations
```js
let resultAddition = 10 + 5; // 15
let resultSubtraction = 20 - 8; // 12
let resultMultiplication = 6 * 7; // 42
let resultDivision = 50 / 2; // 25
let resultModulus = 17 % 4; // 1 (remainder of 17 divided by 4)

```

### Math Operations
We are also having a mathematical object that is responsible for various mathematical operations. The most commonly ones are

```js
1. Math.sqrt(x): Returns the square root of x.
2. Math.pow(x, y): Returns x raised to the power of y.
3. Math.abs(x): Returns the absolute (positive) value of x.
4. Math.round(x): Rounds x to the nearest integer
5. Math.floor(x): Rounds x down to the nearest integer.
6. Math.ceil(x): Rounds x up to the nearest integer.
```
### Increment and Decrement

JavaScript provides shorthand notations for increment and decrement operations:
x++ is equivalent to x = x + 1 (Post-increment).
x-- is equivalent to x = x - 1 (Post-decrement).
++x is equivalent to x = x + 1 (Pre-increment).
--x is equivalent to x = x - 1 (Pre-decrement).

```js
let count = 5;
count++; // count is now 6
count--; // count is now 5

```

### NaN (Not-a-Number):

JavaScript uses NaN to represent the result of an undefined or unrepresentable mathematical operation.

```js
let result = "Hello" / 2; // NaN
```

### Infinity and -Infinity:

JavaScript uses Infinity and -Infinity to represent positive and negative infinity, respectively. These values can result from certain operations like dividing a number by zero.

```js
let positiveInfinity = Infinity;
let negativeInfinity = -Infinity;

let result1 = 1 / 0; // positiveInfinity
let result2 = 5 * Infinity; // positiveInfinity
let result3 = -1 / 0; // negativeInfinity
```