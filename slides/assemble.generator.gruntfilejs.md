Gruntfile.js
```javascript
assemble: {
    options: {
        flatten: true,
        assets: '<%= config.dist %>/assets',
        layout: 'default.hbs',
        layoutdir: '<%= config.src %>/templates/layouts/',
        data: '<%= config.src %>/data/*.{json,yml}',
        partials: '<%= config.src %>/templates/partials/*.hbs',
        plugins: ['assemble-contrib-permalinks'],
    },
```

```javascript
    // Targets
    server: {
        files: {
            '.tmp/': ['<%= config.src %>/templates/pages/**/*.hbs']
        }
    },
    dist: {
        files: {
            '<%= config.dist %>/': ['src/templates/pages/**/*.hbs']
        }
    }
},
```
<!-- .element: class="fragment" -->
