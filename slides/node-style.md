## `node-style`

```javascript
YUI().use('node-base','node-style',function(Y) {
    var myNode = Y.one('#my-node');

    // NOTE: camel case, not hyphenated
    myNode.getStyle('backgroundColor');
    myNode.getComputedStyle('width');

    // NOTE: Rather use a CSS class
    myNode.setStyle('display', 'none');
});
```
<!-- .element: class="fragment" -->
