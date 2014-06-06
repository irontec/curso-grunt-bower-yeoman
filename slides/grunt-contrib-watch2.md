
Gruntfile.js
```javascript
    watch: {
        sass: {
            files: ['<%= config.app %>/styles/{,*/}*.{scss,sass}'],
            tasks: ['sass:server', 'autoprefixer']
        },

        js: {
            files: ['<%= yeoman.app %>/scripts/{,*/}*.js'],
            tasks: ['newer:jshint:all'],
            options: {
                livereload: true
            }
        },
    }
```
