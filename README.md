# `STRINGS` , `NUMBERS` and `METHODS` in JAVASCRIPT
![image](https://github.com/user-attachments/assets/7bd30338-4587-49d6-b8ea-f6fd50a1c503)
![image](https://github.com/user-attachments/assets/b0320a66-d082-4a98-9333-7af92978f01a)
## What is a Method in JavaScript?

In JavaScript, a method is a function that is associated with an object. Methods are actions that can be performed on objects. When a function is a property of an object, it is called a method. Methods are used to perform various tasks, like manipulating data, and are often used to interact with and manipulate strings and numbers.

## Introduction

This document provides an overview of Strings and Numbers in JavaScript and their associated methods. Understanding these fundamental data types and their methods is essential for efficient and effective JavaScript programming.

## Strings

A string in JavaScript is a sequence of characters used to represent text. Strings can be created using single quotes, double quotes, or backticks (for template literals).

### Examples of String Methods

#### `at(index)`

Returns the character at the specified index.

```javascript
let str = 'Hello, World!';
console.log(str.at(7)); // 'W'
```

#### `trim()`

Removes whitespace from both ends of a string.

```javascript
let str = '  Hello, World!  ';
console.log(str.trim()); // 'Hello, World!'
```

#### `toUpperCase()`

Converts all the characters in a string to uppercase.

```javascript
let str = 'Hello, World!';
console.log(str.toUpperCase()); // 'HELLO, WORLD!'
```

#### `toLowerCase()`

Converts all the characters in a string to lowercase.

```javascript
let str = 'Hello, World!';
console.log(str.toLowerCase()); // 'hello, world!'
```

#### `slice(start, end)`

Extracts a section of a string and returns it as a new string.

```javascript
let str = 'Hello, World!';
console.log(str.slice(7, 12)); // 'World'
```

#### `substring(start, end)`

Returns the part of the string between the start and end indexes.

```javascript
let str = 'Hello, World!';
console.log(str.substring(7, 12)); // 'World'
```

#### `split(separator)`

Splits a string into an array of substrings.

```javascript
let str = 'Hello, World!';
console.log(str.split(', ')); // ['Hello', 'World!']
```

#### `replace(searchValue, newValue)`

Replaces a specified value with another value in a string.

```javascript
let str = 'Hello, World!';
console.log(str.replace('World', 'JavaScript')); // 'Hello, JavaScript!'
```

#### `charAt(index)`

Returns the character at the specified index.

```javascript
let str = 'Hello, World!';
console.log(str.charAt(7)); // 'W'
```

#### `concat(string1, string2, ...)`

Concatenates the string arguments to the calling string and returns a new string.

```javascript
let str1 = 'Hello';
let str2 = 'World';
console.log(str1.concat(', ', str2, '!')); // 'Hello, World!'
```

#### `replaceAll(searchValue, newValue)`

Replaces all occurrences of a specified value with another value in a string.

```javascript
let str = 'Hello, World! World is beautiful!';
console.log(str.replaceAll('World', 'JavaScript')); // 'Hello, JavaScript! JavaScript is beautiful!'
```

#### `includes(searchString)`

Determines whether one string may be found within another string.

```javascript
let str = 'Hello, World!';
console.log(str.includes('World')); // true
```

#### `indexOf(searchValue)`

Returns the index within the calling String object of the first occurrence of the specified value.

```javascript
let str = 'Hello, World!';
console.log(str.indexOf('World')); // 7
```

#### `repeat(count)`

Constructs and returns a new string which contains the specified number of copies of the string on which it was called, concatenated together.

```javascript
let str = 'Hello';
console.log(str.repeat(3)); // 'HelloHelloHello'
```

## Numbers

Numbers in JavaScript are a numeric data type that can be used to represent both integer and floating-point numbers.

### Examples of Number Methods

#### `Math.round()`

Rounds a number to the nearest integer.

```javascript
let num = 4.6;
console.log(Math.round(num)); // 5
```

#### `Math.floor()`

Returns the largest integer less than or equal to a given number.

```javascript
let num = 4.6;
console.log(Math.floor(num)); // 4
```

#### `Math.ceil()`

Returns the smallest integer greater than or equal to a given number.

```javascript
let num = 4.1;
console.log(Math.ceil(num)); // 5
```

#### `Math.min()`

Returns the smallest of zero or more numbers.

```javascript
console.log(Math.min(1, 2, 3)); // 1
```

#### `Math.max()`

Returns the largest of zero or more numbers.

```javascript
console.log(Math.max(1, 2, 3)); // 3
```

#### `Math.pow(base, exponent)`

Returns the base to the exponent power.

```javascript
console.log(Math.pow(2, 3)); // 8
```

#### `Math.sqrt(number)`

Returns the square root of a number.

```javascript
console.log(Math.sqrt(9)); // 3
```

#### `Math.abs(number)`

Returns the absolute value of a number.

```javascript
console.log(Math.abs(-5)); // 5
```

#### `Math.random()`

Returns a pseudo-random number between 0 and 1.

```javascript
console.log(Math.random()); // e.g. 0.123456789
```

#### `isNaN(value)`

Determines whether a value is NaN (Not-a-Number).

```javascript
console.log(isNaN('Hello')); // true
```
