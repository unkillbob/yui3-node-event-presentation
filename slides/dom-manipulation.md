## DOM Manipulation

```javascript
// YUI 2
YAHOO.util.Dom.addClass(el, 'my-class');
```
<!-- .element: class="fragment" -->

```javascript
// Y.DOM
YUI().use('dom-base', function(Y) {
    Y.DOM.addClass(el, 'my-class');
});
```
<!-- .element: class="fragment" -->

- Both normalize browser inconsistencies/bugs.
<!-- .element: class="fragment" -->
