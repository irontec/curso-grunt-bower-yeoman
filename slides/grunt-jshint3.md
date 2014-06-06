Gruntfile.js
```javascript
  // Make sure code styles are up to par and there are no obvious mistakes
  jshint: {
    options: {
      jshintrc: '.jshintrc',
      reporter: require('jshint-stylish')
    },
    // Check the node backend files
    server: {
      options: {
        jshintrc: 'lib/.jshintrc'
      },
      src: [ 'lib/{,*/}*.js']
    },
  },
```
