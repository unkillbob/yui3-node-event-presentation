##  Attributes

```javascript
// Set valid HTML attribute
myNode.set('title', 'Hover to see me!');
myNode.set('data-foo', 'bar');
```
<!-- .element: class="fragment" -->

```javascript
// Set custom attributes (discouraged)
myNode.setAttribute('custom-attr', '!');
```
<!-- .element: class="fragment" -->

```javascript
// Set multiple attributes
myNode.setAttrs({
    title: 'A title',
    'data-foo': 'bar'
});
```
<!-- .element: class="fragment" -->
