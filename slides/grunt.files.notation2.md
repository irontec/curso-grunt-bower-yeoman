#### Building the files object dynamically

```javascript
files: [
  {
    expand: true,     // Enable dynamic expansion.
    cwd: 'lib/',      // Src matches are relative to this path.
    src: ['**/*.js'], // Actual pattern(s) to match.
    dest: 'build/',   // Destination path prefix.
    ext: '.min.js',   // Dest filepaths will have this extension.
    extDot: 'first',  // Extensions in filenames begin after the first dot
    flatten: false    // Remove all path parts from generated dest paths.
  },
],
```
