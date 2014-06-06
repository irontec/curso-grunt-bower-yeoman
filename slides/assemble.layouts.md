# Layouts

Layouts are used for "wrapping" the content of individual pages with common elements

```
src/
└── templates
    └── layouts
        ├── sidebar.hbs
        └── default.hbs
```

Gruntfile.js
```javascript
assemble: {
  options: {
    layout: 'default.hbs',
    layoutdir: '<%= config.src %>/templates/layouts/',
  },
  // Targets with parametrized options
  docs: {
    options: {layout: 'docs-layout.hbs' },
    files: {'docs/': ['src/docs/*.hbs' ]},
  },
  site: {
    options: {layout: 'site-layout.hbs' },
    files: {'site/': ['src/site/*.hbs' ]},
  }
}
```
