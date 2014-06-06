Gruntfile.js

```javascript
bowerInstall: {
    app: {
        src: [
            // html support
            '<%= config.app %>/index.html'
            '<%= config.app %>/**/*.html',
            // jade support
            '<%= config.app %>/views/**/*.jade',
            // .scss & .sass support
            '<%= config.app %>/styles/main.scss',
        ],
        exclude: ['bower_components/bootstrap/dist/js/bootstrap.js']
    }
},
```

