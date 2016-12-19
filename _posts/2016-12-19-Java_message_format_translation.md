---
title: MessageFormat in JavaScript
---

MessageFormat takes a set of objects, formats them, then inserts the formatted strings into the pattern at the appropriate places.

It provides a means to produce concatenated messages in a language-neutral way. 

**Java MessageFormat example:** 

```javascript
String text = MessageFormat.format("You're about to delete {0} rows.", 5);
```

