# Custom Two Way Binding
Until now, we've been usin ngModel for two way binding but there is a need to see what goes on with it under the hood. 
Two way binding is nothing more than the combination of input and output variables on the same property and we are looking to implement that in this project.

* We first create an input variable to receive the dimensions keyed into the input boxes from our app component and then store them in a property, with which we will update the size of our rectangle
* The output bit is slightly different from what we have been doing till now though. we need to use the same name of our input property, suffixed with 'Change'.
* We'll then have a method emit whatever data we want implemented and then add the property unto the selector in it's parent.
* This time around we dont add a new property but wrap the existing property for the input with brackets - so it gets the box of bananas look.