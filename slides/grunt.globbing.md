#### Globbing patterns

* ```*``` matches any number of characters, but not /
* ```?``` matches a single character, but not /
* ```**``` matches any number of characters, including /, as long as it's the only thing in a path part
* ```{}``` allows for a comma-separated list of "or" expressions
* ```!``` at the beginning of a pattern will negate the match

<br>

#### Tricky examples
```javascript
// Here, bar.js is first, followed by the remaining files, in alpha order:
{src: ['foo/bar.js', 'foo/*.js'], dest: ...}

// All files except for bar.js, in alpha order:
{src: ['foo/*.js', '!foo/bar.js'], dest: ...}
```
