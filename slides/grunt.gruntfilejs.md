## Gruntfile.js

```javascript
'use strict';
// wrapper function
module.exports = function (grunt) {
```

```javascript
  // Load grunt tasks automatically
  require('load-grunt-tasks')(grunt);
``` 
<!-- .element: class="fragment" -->

```javascript
  // Define the configuration for all the tasks
  grunt.initConfig({
  });
``` 
<!-- .element: class="fragment" -->

```javascript
  // Load manually a plugin.
  grunt.loadNpmTasks('grunt-contrib-uglify');
```
<!-- .element: class="fragment" -->

```javascript
  // Define custom tasks and aliases
  grunt.registerTask('wait', function () {});

  grunt.registerTask('default', [
    'newer:jshint',
    'build'
  ]);
};
```
<!-- .element: class="fragment" -->
