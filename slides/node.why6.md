```javascript
db.query("select..", function (result) {
    // callback
});
```
* Allows the program to return to the event loop immediately.

* This is how I/O should be done. <!-- .element: class="fragment" -->

* every I/O call must take a callback <!-- .element: class="fragment" -->

* JavaScript lacked an existing I/O API <!-- .element: class="fragment" -->
