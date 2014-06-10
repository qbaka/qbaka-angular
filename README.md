[Qbaka](https://qbaka.com) Angular Plugin
=============

[Qbaka](https://qbaka.com) is a SaaS that automatically tracks all JavaScript errors on you web page. AngularJS wraps all your code with try-catch blocks thus preventing [Qbaka](https://qbaka.com) from tracking exceptions. This plugin listens for Angular errors and reports it to qbaka. 

API
---

```JavaScript
qbaka.angular = function (app, apiKey);
```
* _app_ This function initialize qbaka with your app module (returned by angular.module function) and
* _apiKey_ API key from qbaka, 128-bit hexadecimal code from your snippet provided by Qbaka service

Sample
----

```JavaScript
var app = angular.module('myApp');
qbaka.angular(app, '1234567890acbdef1234567890acbdef'); // Last parameter is your Qbaka 
// Continue your stuff
```

Installation
------------

* Download qbaka-angular.js from this repository
* If you use bower, type: ```bower instal qbaka-angular```
