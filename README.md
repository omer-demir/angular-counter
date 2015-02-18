# Angular-Counter
Angular counter is simple counter. With this widget you can easily count 0 to given number. It is easy to use.

```javascript
angular.module('app',[angular-count]).controller('baseCntrl',function($scope)
  {
    $scope.valueToCount=10;
  });
```
```html
<div ng-controller="baseCntrl">
  <div count-up value-to-count="valueToCount" speed="10"/>
</div>
  ```
This code will simply count from 0 to 10 with 10 ms. 

I used only `$interval` dependency for directive.

The sample can be found in codepen

http://codepen.io/omer-demir/pen/wByZRg
