##  Back to Front

Selectors are evaluated back to front.

```javascript
// Bad
Y.one('.my-class div');
```
<!-- .element: class="fragment" -->

```javascript
// Better
Y.one('.my-class > .my-specific-class');
```
<!-- .element: class="fragment" -->
