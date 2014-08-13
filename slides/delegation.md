##  Delegation

```javascript
YUI().use('node-base','node-event-delegate',function(Y) {
    var taskList = Y.one('.prf-tasklist');

    taskList.delegate('click', function(event) {
        var button = event.currentTarget,
            task = button.ancestor('.prf-task');

        markTaskComplete(task);
    }, '.prf-done');
});
```

- One event binding for all tasks
<!-- .element: class="fragment" -->
