# aPopup
aPopup is a jquery plugin based on the existing bPopup plugin (**v 0.11.0**), the goal of this project is using the foundation given by bPopup in order to improve it 


#### CHANGE LOG
**v 1.0.1**
+  initializing with aPopup instead of bPopup
```javascript
$('#example').bPopup()
//is now
$('#example').aPopup()
```
+ closing class changed from 'b-close' to 'a-close'
+ onClose event now receives the selector element that triggered the closing action as a parameter
```javascript
$('#example').aPopup({
     onClose: function() {      

     }
 });
 //$elm is the element that triggered the closing action
 $('#example').aPopup({
      onClose: function($elm) {   

      }
  });   
```
___
##### DISCLAIMER
This project is not directly connected in any way with bPopup, for more information about bPopup visit http://dinbror.dk/bPopup
