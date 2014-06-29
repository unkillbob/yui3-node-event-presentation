##  Content

```javascript
    // Plain text: HTML escaped
    myNode.set('text', 'Hi!');
    myNode.get('text'); //=> "Hi!"
```
<!-- .element: class="fragment" -->

```javascript
    // HTML: not escaped
    myNode.setHTML('<p>Hi!</p>');
    myNode.getHTML(); //=> "<p>Hi!</p>"
```
<!-- .element: class="fragment" -->
