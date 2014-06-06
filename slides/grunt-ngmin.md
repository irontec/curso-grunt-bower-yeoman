## Grunt ngmin

https://github.com/btford/grunt-ngmin

Grunt plugin for pre-minifying Angular apps

Turns this
```javascript
angular.module('whatever').controller('MyCtrl', function ($scope, $http) { ... });
```

Into
```javascript
angular.module('whatever').controller('MyCtrl', ['$scope', '$http', function ($scope, $http) { ... }]);
```
