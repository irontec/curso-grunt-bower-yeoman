
Añadir la regla configureProxies antes de arrancar el servidor connect

```javascript
grunt.registerTask('server', function (target) {
grunt.task.run([
...
'configureProxies:server',
'livereload-start',
'connect:livereload',
...
```

Añadir el proxy en la tarea connect

```javascript
connect: {
    proxies: [
        {
            context: '/',
            host: 'localhost'
        }
    ]
}
```

https://github.com/drewzboto/grunt-connect-proxy

proxies: [
    context: '/context',
    host: 'host',
    port: 8080,
    rewrite: {
        '^/removingcontext': '',
        '^/changingcontext': '/anothercontext'
    }
]