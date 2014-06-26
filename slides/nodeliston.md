## `NodeList.on`?

```javascript
YUI().use('node-base','event-base',function(Y) {
    var tasks = Y.all('.task');

    tasks.on('click', function(event) {
        markTaskComplete(event.target);
    });
})
```
<!-- .element: class="fragment" -->

- One event binding per DOM node!
<!-- .element: class="fragment" -->
