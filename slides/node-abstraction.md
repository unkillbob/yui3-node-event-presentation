##  Node Abstraction

```javascript
YUI().use('node-base', function(Y) {
    var myNode = /* spoiler alert! */;

    myNode.addClass('my-class')
        .set('text', 'Hello World!')
        .show();
        //.etc()
});
```

- Still normalizes inconsistencies/bugs
- Better API (terse, method chaining)
