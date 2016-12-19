---
title: Force update set
---
Force into update set, replace GR and assign sysid

```javascript
var gr = new GlideRecord('TABLE_NAME[FROM]');
gr.addQuery('sys_id', '45494f95379fe2007a9e12c543990ea4')
gr.query()
gr.next()
//Current update set
var um = new GlideUpdateManager2();
um.saveRecord(gr)
```
