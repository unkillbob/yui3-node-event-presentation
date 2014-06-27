## `Node.one`

```javascript
YUI().use('node-base', function(Y) {
    var myNode = Y.one('#my-node');
    // Only find descendants of myNode
    myNode.one('.my-class');
});
```
<!-- .element: class="fragment" -->

- Faster searching of smaller DOM tree
<!-- .element: class="fragment" -->

- Useful if already have reference to existing Node
<!-- .element: class="fragment" -->

- Combining selectors can be faster than chaining
<!-- .element: class="fragment" -->
