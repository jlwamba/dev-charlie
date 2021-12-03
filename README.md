# angular
```angular.html``` helps us create a controller to get data using code.

```javascript
window.app = angular.module('hi-angular,[]');
app.controller('MainController', function($scope, $http ){
    $scope.user = null;

    $http.get('/user').then(response => {
        console.log(response.data);
    });

});
```


from the response of the ```('/user')```, this will return the ```user.json```

