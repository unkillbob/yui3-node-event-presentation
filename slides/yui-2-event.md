##  YUI 2 Event

```javascript
var Event = YAHOO.util.Event;

Event.on(el,'click',function(event) {
    Event.preventDefault(event);

    var target = Event.getTarget(event);

    doAwesomeThings(target);
});
```
