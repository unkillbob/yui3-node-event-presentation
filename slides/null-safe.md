## Empty not `null`

```javascript
YUI().use('node-base', function(Y) {
    var noNodes = Y.all('.does-not-exist');

    console.log(noNodes.size()); //=> 0

    // No Error thrown!
    noNodes.addClass('my-class');
});
```
