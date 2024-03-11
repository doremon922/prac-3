# prac-3
Practical-03 
Title: -Write a program to perform validation of a form using AngularJS. 
Programs: 
<!DOCTYPE html> 
<html> 
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.9/angular.min.js"> </script>   
<body> 
 
<h2>Form Validation</h2> 
 
<form ng-app="myApp" ng-controller="validateCtrl" name="myForm" novalidate> 
 
<p>Username:<br> 
<input type="text" name="user" ng-model="user" required> 
<span style="color:red" ng-show="myForm.user.$dirty && myForm.user.$invalid"> 
