
Generated configuration for concat and uglify tasks

```javascript
{
  concat: {
    '.tmp/concat/js/main.js': [
      'app/js/app.js',
      'app/js/controllers/thing-controller.js',
      'app/js/models/thing-model.js',
      'app/js/views/thing-view.js'
    ]
  },
  uglifyjs: {
    'dist/js/main.js': ['.tmp/concat/js/main.js']
  }
}
```
