# `STRINGS` , `NUMBERS` and `METHODS` in JAVASCRIPT
![image](https://github.com/user-attachments/assets/7bd30338-4587-49d6-b8ea-f6fd50a1c503)
![image](https://github.com/user-attachments/assets/b0320a66-d082-4a98-9333-7af92978f01a)
# Strings and Numbers in JavaScript

## Introduction
In JavaScript, strings and numbers are fundamental data types that have a wide range of built-in methods to perform various operations. This README provides an overview of these data types and some of their common methods.

## What is a Method in JavaScript?
A method in JavaScript is a function that is associated with an object. Methods are actions that can be performed on objects. For example, string and number methods are functions that are associated with the String and Number objects, respectively.

## Strings
A string is a sequence of characters used to represent text. Strings in JavaScript are immutable, meaning once a string is created, it cannot be changed. However, you can create new strings based on operations performed on existing strings.

### Common String Methods
![image](https://github.com/user-attachments/assets/7e80b01d-0a9e-4c69-b110-38993e40ee20)
- `toUpperCase()`: Converts the string to uppercase.
  ```javascript
  let str = "hello";
  console.log(str.toUpperCase()); // Output: "HELLO"
  ```

- `toLowerCase()`: Converts the string to lowercase.
  ```javascript
  let str = "HELLO";
  console.log(str.toLowerCase()); // Output: "hello"
  ```

- `charAt(index)`: Returns the character at the specified index.
  ```javascript
  let str = "Hello, World!";
  console.log(str.charAt(0)); // Output: "H"
  ```

- `substring(start, end)`: Returns a substring between the start and end indices.
  ```javascript
  let str = "Hello, World!";
  console.log(str.substring(0, 5)); // Output: "Hello"
  ```

- `replace(searchValue, newValue)`: Replaces occurrences of searchValue with newValue.
  ```javascript
  let str = "Hello, World!";
  console.log(str.replace("World", "JavaScript")); // Output: "Hello, JavaScript!"
  ```

- `split(separator)`: Splits the string into an array of substrings based on the separator.
  ```javascript
  let str = "Hello, World!";
  console.log(str.split(", ")); // Output: ["Hello", "World!"]
  ```

## Numbers
Numbers in JavaScript are used to represent both integer and floating-point values. JavaScript uses a double-precision floating-point format for all its numeric values.

### Common Number Methods
- `toString()`: Converts the number to a string.
  ```javascript
  let num = 123;
  console.log(num.toString()); // Output: "123"
  ```
