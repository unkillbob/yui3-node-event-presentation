##  Classy

```javascript
YUI().use('node-base', function(Y) {
    var myNode = Y.one('.bar');

    myNode.addClass('foo')
        .removeClass('bar');

    myNode.hasClass('foo'); //=> true
    myNode.hasClass('bar'); //=> false
});
```
