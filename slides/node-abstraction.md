## `Y.Node`: Abstraction

```javascript
YUI().use('node-base', function(Y) {
    var myNode = /* spoiler alert! */;

    myNode.addClass('my-class')
        .set('text', 'Hello World!')
        .show();
        //.etc()
});
```
<!-- .element: class="fragment" -->

- Still normalizes inconsistencies/bugs
<!-- .element: class="fragment" -->

- Better API (terse, method chaining)
<!-- .element: class="fragment" -->
