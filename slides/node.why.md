
http://s3.amazonaws.com/four.livejournal/20091117/jsconf.pdf

```javascript
var result = db.query("select * from T");
```

* What is the software doing while it queries the database?

* either blocks the entire process or implies multiple execution stacks. <!-- .element: class="fragment" -->

* Other threads of execution can run while waiting. <!-- .element: class="fragment" -->
