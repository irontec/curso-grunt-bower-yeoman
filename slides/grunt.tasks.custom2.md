Example: wait untill the server is up

```javascript
grunt.registerTask('wait', function () {
    var interval, socket, done = this.async();
    grunt.log.ok('Waiting for server reload...');

    socket = new require('net').Socket();
    socket.on('error', function () {});
    socket.connect(grunt.config.data.yeoman.port, function () {
        socket.destroy();
        clearInterval(interval);
        grunt.log.writeln('Done waiting!');
        done();
    });

    interval = setInterval(function () {
        socket.connect(grunt.config.data.yeoman.port);
    }, 100);
});
```
