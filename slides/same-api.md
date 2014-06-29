## Same API as `Y.Node`

### ... mostly
<!-- .element: class="fragment" -->

```javascript
YUI().use('node-base', function(Y) {
    var myNodes = /* spoiler alert! */;

    myNodes.addClass('my-class')
        .removeClass('my-other-class'),
        .set('data-foo', 'bar'),
        .hide();
        //.etc()
});
```
<!-- .element: class="fragment" -->
