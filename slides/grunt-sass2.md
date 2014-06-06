```javascript
sass: {
    options: {
        sourceMap: true,
        loadPath: [
            'bower_components'
        ]
    },
    server: {
        files: [{
            expand: true,
            cwd: '<%= config.app %>/styles',
            src: ['*.scss'],
            dest: '.tmp/styles',
            ext: '.css'
        }]
    }
},
```
