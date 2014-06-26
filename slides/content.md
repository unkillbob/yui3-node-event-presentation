##  Content

```javascript
YUI().use('node-base', function(Y) {
    var myNode = Y.one('#my-node');

    myNode.set('text', 'Hi!');
    myNode.get('text'); //=> "Hi!"

    myNode.setHTML('<p>Hi!</p>');
    myNode.getHTML(); //=> "<p>Hi!</p>"
});
```
