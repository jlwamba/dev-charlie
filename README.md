# angular
Angular adds structure and design patterns to front-end development, allowing developers to create more advanced web applications that are easier to maintain and update.
In the code snippt below, there  is s focused on the home page


```angular.html``` helps us create a controller to get data using code.

```javascript
window.app = angular.module('hi-angular,[]');
app.controller('MainController', function($scope, $http ){
    $scope.user = null;

    $http.get('/user').then(response => {
        console.log(response.data);
    });
});
``



from the response of the ```('/user')```, this will return the ```user.json``` tto return the ```user.json``` file

```javscript
{
    "name": "Jerry Lwamba",
    "repo": Https://www.github.com/jlwamba
}

```` 


