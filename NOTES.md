Node
====

### What is Node?

- [x] native APIs not so great - bugs & inconsistencies
- [x] DOM abstraction
- [x] Y.DOM
- [x] Wraps HTML element -> better API (+ chaining)

### The One

- [x] Y.one
- [x] CSS selectors -> back to front
- [x] not null-safe

### What does Node do?

- [x] set/get content
- [x] add/remove/has classes
- [x] set/get attributes // discourage custom attrs (use data attrs)
- [x] Node.one

### NodeList

- [x] collection of Nodes
- [x] mostly same API as Node
- [x] null/empty safe

### Do I need any other node-* modules besides node-base?

- [x] No
- [x] Well maybe - API docs should say what you need
- [x] _Don't use `node`?_
- [x] node-style

### Learn More

- [x] migrating from YUI 2 (http://yuilibrary.com/yui/docs/node/#node-migration)
- [x] migrating from jQuery (http://www.jsrosettastone.com/)
- [x] read more (http://yuilibrary.com/yui/docs/ & http://yuilibrary.com/yui/docs/node/)

### Questions on Node

Event
=====

### What is Event?

- [x] vs onclick
- [x] browser APIs
- [x] YAHOO.util.Event

### Subscribing to Events

- [x] Node.on
- [x] `event` facade
- [x] preventDefault() / stopPropagation()

### Event Delegation

- [x] Event bubbling
- [x] Tasklist example
- [x] Node.delegate

### Lazy Binding

- [x] Y.on and Y.delegate // caution

### Key Events

- [ ] event-key

### Extras for Experts

- [ ] event-focus
- [ ] event-mouseenter
- [ ] event-mousewheel
- [ ] event-touch
- [ ] event-tap

Homeless
========
_Topics that need to go somewhere, just not sure where._

- [x] modules (node-base, event-base, etc)
- [ ] caching nodes (i.e. saving references)
