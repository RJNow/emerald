---
title: Primitive values and Object literal 
---
Java has eight Primitive types:   
* Byte  
* Short  
* Int  
* Long    
* Char   
* Boolean   
* Float   
* Double  
*Anything else is a non-primitive type.*  


A JavaScript Object literal is a comma-separated list of name-value pairs wrapped in curly braces. Object literals encapsulate data, enclosing it in a tidy package.  

**The following is an example of an number/string literal:**  

```javascript
var car = { manyCars: {a: "Saab", "b": "Jeep"}, 7: "Mazda" };

console.log(car.manyCars.b); // Jeep
console.log(car[7]); // Mazda
```
  
**Using typeOf:**  

```javascript
var s = new String("dummy"); //Creates a String object
console.log(s); //"dummy"

console.log(typeof s); //"object"

var nonObject = "1" + "2"; //Create a String primitive 
console.log(typeof nonObject); //"string"

var objString = new String("1" + "2"); //Creates a String object
console.log(typeof objString); //"object"
```