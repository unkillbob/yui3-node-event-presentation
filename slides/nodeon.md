## `Node.on`

```javascript
YUI().use('node-base','event-base',function(Y) {
    var myNode = Y.one('#my-node');

    myNode.on('click', function(event) {
        event.preventDefault();

        doAwesomeThings();
    });
});
```
