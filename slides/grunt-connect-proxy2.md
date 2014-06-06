Add a proxy to avoid CORS issues when developing against a backend 

```javascript
connect: { ...
    livereload: {
        options: {
            middleware: function(connect) {
                return [
                    ...
                    connect.static(config.app),
                    require('grunt-connect-proxy/lib/utils').proxyRequest,
                ];
            }
        }
    },
    proxies: [{
            context: '/',
            host: 'localhost'
    }]
}
```
