
```
function A() {
    this["a"] = 1;
    this["b"] = true;
    this["c"] = [1,2,3];
}

function B() {
    this["a"] = 1;
    this["b"] = true;
    this["c"] = [1,2,3];
}

A.prototype = new B();

var object = new A();
```