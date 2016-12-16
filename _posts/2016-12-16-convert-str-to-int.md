---
title: Converting from string to int/float
---
use parseInt() and parseFloat() to convert from string to int/float

you can also apply a code that checks if its not a number =

```javascript
var underterminedValue = "elephant";
if (isNaN(parseInt(underterminedValue,2))) 
{
   console.log("Handle not a number case");
}
else{
  console.log("Handle is number case");
}
```
