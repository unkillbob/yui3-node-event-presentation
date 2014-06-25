## `Y.one`

```javascript
YUI().use('node-base', function(Y) {
    // Get by CSS selector
    var myNode = Y.one('.css-class'),
        nodeById = Y.one('#id');

    // Wrap HTMLElement
    var bodyNode = Y.one(document.body);
});
```
