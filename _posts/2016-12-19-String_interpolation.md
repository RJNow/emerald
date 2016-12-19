---
title: Template literals
---
Is a new way to create a String. It's introduced in ES6, where were given more control over dynamic strings in our programs. 

To create a template literal, instead of single quotes (') or double quotes (") quotes we use the backtick (`) character. This will produce a new string, and we can use it in any way we want.


```javascript
// Basic interpolation
var name = 'David';
console.log(`Hi, my name is ${name}`); // Hi, my name is David

// Math :)
var one = 1;
var two = 2;
console.log(`Your total is: ${one+two}`); // Your total is: 3

// More math
console.log(`Another total is: ${one + two * 2}`); // Another total is: 5

// Object properties
var obj = { x: 1, y: 2 };
console.log(`Your total is: ${obj.x + obj.y}`); // Your total is: 3
```