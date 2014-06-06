
```
// Object.defineProperties
var a = {
  "a": { value: "hello" },
  "b": { value: true },
  "c": {
    get: function() { return true },
    set: function(value) { console.log("Setting `b` to", value) }
  }
};

var b = {
    "a": 1,
    "b": true,
    "c": [1,2,3]
};

var object = Object.create(b, a);

```
