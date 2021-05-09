# JavaScript Functions

A JavaScript function is a block of code designed to perform a particular task.

A JavaScript function is executed when "something" invokes it (calls it).

For example:


function myFunction(p1, p2) {

  return p1 * p2;   // The function returns the product of p1 and p2

}



A JavaScript function is defined with the function keyword, followed by a name, followed by parentheses ().

Function names can contain letters, digits, underscores, and dollar signs (same rules as variables).

*The parentheses may include parameter names separated by commas:*
(parameter1, parameter2, ...)

**The code to be executed, by the function, is placed inside curly brackets:** {}

Primitive parameters (such as a number) are passed to functions by value;

the value is passed to the function, but if the function changes the value of the parameter, this change is not reflected globally or in the calling function.

If you pass an object (i.e. a non-primitive value, such as Array or a user-defined object) as a parameter and the function changes the object's properties,
that change is visible outside the function
