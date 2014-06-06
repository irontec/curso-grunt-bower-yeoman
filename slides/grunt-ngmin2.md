```javascript
// Allow the use of non-minsafe AngularJS files. Automatically makes it
// minsafe compatible so Uglify does not destroy the ng references
ngmin: {
  dist: {
    files: [{
      expand: true,
      cwd: '.tmp/concat/scripts',
      src: '*.js',
      dest: '.tmp/concat/scripts'
    }]
  }
},
```
