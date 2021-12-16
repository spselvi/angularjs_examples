Angular js:
    AngularJS is a JavaScript framework. It can be added to an HTML page with a <script> tag.
      AngularJS extends HTML attributes with Directives and Expression
  ex:
  <script src="htpps://angular.org/1.6.9/angular.js"></script>
 ng Directives:
   ng-app -Its define the angular js application
   ng-model-Its binds the value of HTML controls (input, select, textarea)
   ng-bind-Its directive binds application data to the HTML view.
  ex:
    <!DOCTYPE html>
     <html>
     <script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.9/angular.min.js"></script>
      <body>
     <div ng-app="">
      <p>Name: <input type="text" ng-model="name"></p>
      <p ng-bind="name"></p>
      </div>
      </body>
      </html>
  ng-init 
      Its initialize the angular js
      ex:
        <div ng-app="" ng-init="firstName='John'">
         <p>The name is <span ng-bind="firstName"></span></p>
          </div>
simple angular js:
<!DOCTYPE html>
<html>
<script src="https://code.angularjs.org/1.6.9/angular.js"></script>
<head>
    <meta chrset="UTF 8">
    <title>simple angular js</title>
</head>
<body ng-app="">
<h3>Angular JS Beginners</h3>
</body>
</html>
