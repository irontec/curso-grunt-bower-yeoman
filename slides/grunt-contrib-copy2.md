```javascript
copy: {
  dist: {
    files: [{
      expand: true,
      dot: true,
      cwd: '<%= yeoman.app %>',
      dest: '<%= yeoman.dist %>/public',
      src: [
        '*.{ico,png,txt}',
        '.htaccess',
        'bower_components/**/*',
        'images/{,*/}*.{webp}',
        'fonts/**/*'
      ]
    }]
  },
},
```
