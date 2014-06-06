#### Files

```javascript
// Compact Format
concat: {
  src: ['src/bb.js', 'src/bbb.js'],
  dest: 'dest/b.js',
},
```

```javascript
// Files Object Format
concat: {
  files: {
    'dest/a.js': ['src/aa.js', 'src/aaa.js'],
    'dest/a1.js': ['src/aa1.js', 'src/aaa1.js'],
  },
},
```

```javascript
// Files Array Format
concat: {
  files: [
    {src: ['src/aa.js', 'src/aaa.js'], dest: 'dest/a.js'},
    {src: ['src/aa1.js', 'src/aaa1.js'], dest: 'dest/a1.js'},
  ],
},
```
