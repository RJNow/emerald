---
title: Primitive values and object literal 
---
Java has eight primitive types: byte , short , int , long , char , boolean , float and double . Anything else is a non-primitive type. 

A JavaScript object literal is a comma-separated list of name-value pairs wrapped in curly braces. Object literals encapsulate data, enclosing it in a tidy package.

```javascript
var s = new String("dummy"); //Creates a String object
console.log(s); //"dummy"

console.log(typeof s); //"object"

var nonObject = "1" + "2"; //Create a String primitive 
console.log(typeof nonObject); //"string"

var objString = new String("1" + "2"); //Creates a String object
console.log(typeof objString); //"object"
```