
Performs rewrites based on rev and the useminPrepare configuration

```javascript
usemin: {
  options: {
      assetsDirs: ['<%= config.dist %>', '<%= config.dist %>/images']
  },
  html: ['<%= config.dist %>/{,*/}*.html'],
  css: ['<%= config.dist %>/styles/{,*/}*.css']
},
```
