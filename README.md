# Reusable AngularJs BootStrap Modal
**Project Description: ** An AngualarJs Modal component based on Bottstrap Modal that is resuable
**Author:** Eric Chen
**Blog:** http://www.hitechchimp.com
# Installation
##### 1. Install BootStrap and Angular-xeditable in your project: 
This modal us Angular-xeditable, so the fisrt step is to include it in your project
https://vitalets.github.io/angular-xeditable/
##### 2. Include the modal componet in your project,
Example: https://github.com/cxywind/WsCRM/blob/master/WsCRM/index.html
##### 3.Add dependency of the Modal
Example: https://github.com/cxywind/WsCRM/blob/master/WsCRM/App/wscrm.module.js

# How to use it?
1. Code in template:
```
<c-modal></c-modal> 
```
2. Code in controller

Example: https://github.com/cxywind/WsCRM/blob/master/WsCRM/App/orders/order.html

Following code is required by xeditable
```
 .run(function(editableOptions) {
      editableOptions.theme = 'bs3'; // xeditable
})
```

Add dependency on utils.
```
controller: function OrderListController($scope, $rootScope, utils) {
```

