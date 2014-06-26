##  Beware the `null`

```javascript
YUI().use('node-base', function(Y) {
    var myNode = Y.one('#not-found');

    console.log(myNode); //=> null

    // Error thrown
    myNode.addClass('my-class');
});
```
<!-- .element: class="fragment" -->
