#### Grunt custom tasks

```javascript
grunt.registerTask('dist', ['concat:dist', 'uglify:dist']);
```

```javascript
grunt.registerTask('foo', 'My "foo" task.', function() {
  grunt.log.writeln('Currently running the "default" task.');
  // Enqueue "bar" and "baz" tasks, to run after "foo" finishes, in-order.
  grunt.task.run('bar', 'baz');
  // Or:
  grunt.task.run(['bar', 'baz']);
});
```
