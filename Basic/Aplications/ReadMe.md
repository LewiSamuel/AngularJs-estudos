# Aplicativos AngularJS

Módulos AngularJS definem aplicativos AngularJS.

Os controladores AngularJS controlam os aplicativos AngularJS.

A diretiva ng-app define o aplicativo, a diretiva ng-controller define o controlador.

```HTML
<!-- Exemplo de AngularJS -->
<div ng-app=" myApp" ng-controller=" myCtrl">

First Name: <input type="text" ng-model="firstName"><br>
Last Name: <input type="text" ng-model="lastName"><br>
<br>
Full Name: {{firstName + " " + lastName}}

</div>

<script>
var app = angular.module(' myApp', []);
app.controller(' myCtrl', function($scope) {
  $scope.firstName= "John";
  $scope.lastName= "Doe";
});
</script> 
```