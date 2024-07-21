# Custom Two Way Binding
Until now, we've been usin ngModel for two way binding but there is a need to see what goes on with it under the hood. 
Two way binding is nothing more than the combination of input and output variables on the same property and we are looking to implement that in this project.

* We first create an input variable to receive the dimensions keyed into the input boxes from our app component and then store them in a property, with which we will update the size of our rectangle
* The output bit is slightly different from what we have been doing till now though.