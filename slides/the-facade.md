##  The Facade

```javascript
myNode.on('click', function(event /*<= this*/) {
    // event instanceof Y.DOMEventFacade

    event.preventDefault();

    event.target; // a Y.Node instance
});
```

- wraps native event
<!-- .element: class="fragment" -->

- normalizes browser differences
<!-- .element: class="fragment" -->

- Y.Node instances for convenience
<!-- .element: class="fragment" -->
