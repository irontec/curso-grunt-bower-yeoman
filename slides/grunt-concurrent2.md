Gruntfile.js
 ```bash
    concurrent: {
      server: [
        'compass:server',
        'jade:compile',
        'copy:styles'
      ],
      dist: [
        'compass:dist',
        'imagemin',
        'svgmin',
        'htmlmin'
      ]
    },
```
