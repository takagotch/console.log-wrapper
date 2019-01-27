### console.log-wrapper
---
https://github.com/patik/console.log-wrapper

```
npm install consolelog
bower install consolelog
```

```js
require(['consolelog'], function(log){
  log('It works!');
});

log.settings({
  lineNumber: true,
  group: {
    label: 'Log:',
    collapsed: false
  }
});

console.log(
  "Here's a string",
  3.14
  {"alpha": 5, "bravo": false},
  document.getElementById('charlie'),
  new Date()
)
```

```
```

