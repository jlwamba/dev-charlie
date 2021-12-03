# angular
```angular.html``` helps us create a controller to get data using code.

<script>
window.app = angular.module('hi-angular,[]');
app.controller('MainController', function($scope, $http ){
    $scope.user = null;

    $http.get('/user').then(response => {
        console.log(response.data);
    });

});

</script>
```

from the response of the ```('/user'), the will return the ```user.json```

