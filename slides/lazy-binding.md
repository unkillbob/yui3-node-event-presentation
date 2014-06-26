##  Lazy Binding

```javascript
YUI().use('event-base', function(Y) {
    Y.on('click', function(event) {
        // ...
    }, '#my-node');

    Y.delegate('click', function(event) {
        // ...
    }, '.prf-tasklist', '.prf-done');
});
```

- Seems robust against Node not being in DOM
<!-- .element: class="fragment" -->

- YUI constantly polling the DOM to check for Node
<!-- .element: class="fragment" -->
