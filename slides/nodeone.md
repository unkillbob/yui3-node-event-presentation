## `Node.one`

```javascript
YUI().use('node-base', function(Y) {
    var myNode = Y.one('#my-node');
    // Only find descendants of myNode
    myNode.one('.my-class');
});
```
<!-- .element: class="fragment" -->

- Combine selectors faster than chaining
<!-- .element: class="fragment" -->

- Useful if already have reference to existing Node
<!-- .element: class="fragment" -->
