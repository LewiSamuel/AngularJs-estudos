# Diretivas AngularJS

Como você já viu, as diretivas AngularJS são atributos HTML com um prefixo ng .

A diretiva ng-init inicializa as variáveis ​​do aplicativo AngularJS.

```html
<!-- Exemplo de AngularJS -->
<div ng-app="" ng-init="firstName='John'">

    <p>The name is <span ng-bind="firstName"></span></p>

</div>
```