#### Closures

Functions which take a small amount of metadata that describes the environment in which they were defined.

```javascript

var counter = (function () {
    var count = 0;
    return function () {
        console.log(count++);
    }
})();

counter(); // 0
counter(); // 1
```
