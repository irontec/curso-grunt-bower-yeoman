```javascript
connect: {
    options: {
        port: 9000,
        open: true,
        livereload: 35729,
        // Change this to '0.0.0.0' to access the server from outside
        hostname: 'localhost'
    },
```
```javascript
    livereload: {
        options: {
            middleware: function(connect) {
                return [
                    // Add created files
                    connect.static('.tmp'),
                    // Add files under /bower_components prefix
                    connect().use('/bower_components', 
                        connect.static('./bower_components')),
                    // Add content under app/
                    connect.static(config.app),
                ];
            }
        }
    },
}
```
