## Save the Nodes!

- Y.Node instances are cached internally
<!-- .element: class="fragment" -->

- Y.one by no means "free" for subsequent executions
<!-- .element: class="fragment" -->

```javascript
// Bad
Y.one('#my-node').addClass('foo');
Y.one('#my-node').show();
```
<!-- .element: class="fragment" -->

```javascript
// Better
var myNode = Y.one('#my-node');
myNode.addClass('foo');
myNode.show();
```
<!-- .element: class="fragment" -->
