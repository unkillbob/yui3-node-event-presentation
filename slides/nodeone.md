## `Node.one`

```javascript
YUI().use('node-base', function(Y) {
    var myNode = Y.one('#my-node');
    // Only find descendants of myNode
    myNode.one('.my-class');
});
```

- Combine selectors > chaining
- Useful if already have reference to existing Node
