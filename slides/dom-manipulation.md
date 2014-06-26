## DOM Manipulation

```javascript
// YUI 2
YAHOO.util.Dom.addClass(el, 'my-class');
```

```javascript
// Y.DOM
YUI().use('dom-base', function(Y) {
    Y.DOM.addClass(el, 'my-class');
});
```

- Both normalize browser inconsistencies/bugs.
