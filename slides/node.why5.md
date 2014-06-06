
* why isn’t everyone using event loops, callbacks, and non-blocking I/O?

* For reasons both cultural and infrastructural.

We are taught to:
```javascript
puts("Enter your name: ");
var name = gets();
puts("Name: " + name);
```

instead of:

```javascript
puts("Enter your name: ");
gets(function (name) {
  puts("Name: " + name);
});
```
