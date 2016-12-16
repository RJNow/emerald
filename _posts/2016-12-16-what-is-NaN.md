---
title: About float numbers
---
when adding two float number e.g. 0.2+0.1==0.3, it will return false because of a constant error, 0.2 is represented as 0.2000000000004 e.g.

to tidy up you can use toPrecision(); (Below is an example)

```javascript
function strip(number) {
    return (parseFloat(number.toPrecision(12)));
}
console.log(strip(12.123456789123456789));
```



